#### Test 558877588826def_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
E/HttpOperation( 6601): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6601): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6601): 	at kfv.a(PG:65)
E/HttpOperation( 6601): 	at kff.u(PG:385)
E/HttpOperation( 6601): 	at kfb.a(PG:29)
E/HttpOperation( 6601): 	at kff.l(PG:132)
E/HttpOperation( 6601): 	at ieo.a(PG:43)
E/HttpOperation( 6601): 	at iep.a(PG:93)
E/HttpOperation( 6601): 	at fhn.a(PG:59)
E/HttpOperation( 6601): 	at lex.a(PG:85)
E/HttpOperation( 6601): 	at lex.b(PG:132)
E/HttpOperation( 6601): 	at fhk.a(PG:1146)
E/HttpOperation( 6601): 	at fhk.a(PG:908)
E/HttpOperation( 6601): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6601): 	at ihi.a(PG:22)
E/HttpOperation( 6601): 	at kft.a(PG:91)
E/HttpOperation( 6601): 	at kfv.a(PG:62)
E/HttpOperation( 6601): 	... 12 more
E/HttpOperation( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6601): 	at gde.c(Unknown Source)
E/HttpOperation( 6601): 	at gde.b(Unknown Source)
E/HttpOperation( 6601): 	at ihi.a(PG:19)
E/HttpOperation( 6601): 	... 14 more
E/ExperimentLoader( 6601): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6601): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6601): 	at kfv.a(PG:65)
E/ExperimentLoader( 6601): 	at kff.u(PG:385)
E/ExperimentLoader( 6601): 	at kfb.a(PG:29)
E/ExperimentLoader( 6601): 	at kff.l(PG:132)
E/ExperimentLoader( 6601): 	at ieo.a(PG:43)
E/ExperimentLoader( 6601): 	at iep.a(PG:93)
E/ExperimentLoader( 6601): 	at fhn.a(PG:59)
E/ExperimentLoader( 6601): 	at lex.a(PG:85)
E/ExperimentLoader( 6601): 	at lex.b(PG:132)
E/ExperimentLoader( 6601): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6601): 	at fhk.a(PG:908)
E/ExperimentLoader( 6601): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6601): 	at ihi.a(PG:22)
E/ExperimentLoader( 6601): 	at kft.a(PG:91)
E/ExperimentLoader( 6601): 	at kfv.a(PG:62)
E/ExperimentLoader( 6601): 	... 12 more
E/ExperimentLoader( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6601): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6601): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6601): 	at ihi.a(PG:19)
E/ExperimentLoader( 6601): 	... 14 more
E/SQLiteLog( 7349): (284) automatic index on view_volumes(volume_id)
--------- beginning of system
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  902): uri = 14 selection = getSealedState
D/SecContentProvider2(  902): mCursor = null
D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
E/HttpOperation( 6601): [getaccountstatus] Unexpected exception
E/HttpOperation( 6601): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6601): 	at kfv.a(PG:65)
E/HttpOperation( 6601): 	at kff.u(PG:385)
E/HttpOperation( 6601): 	at kfb.a(PG:29)
E/HttpOperation( 6601): 	at ixd.a(PG:248)
E/HttpOperation( 6601): 	at ixd.b(PG:206)
E/HttpOperation( 6601): 	at ixd.a(PG:175)
E/HttpOperation( 6601): 	at fig.a(PG:78)
E/HttpOperation( 6601): 	at lex.a(PG:85)
E/HttpOperation( 6601): 	at lex.b(PG:132)
E/HttpOperation( 6601): 	at fhk.a(PG:1146)
E/HttpOperation( 6601): 	at fhk.a(PG:908)
E/HttpOperation( 6601): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6601): 	at ihi.a(PG:22)
E/HttpOperation( 6601): 	at kft.a(PG:91)
E/HttpOperation( 6601): 	at kfv.a(PG:62)
E/HttpOperation( 6601): 	... 12 more
E/HttpOperation( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6601): 	at gde.c(Unknown Source)
E/HttpOperation( 6601): 	at gde.b(Unknown Source)
E/HttpOperation( 6601): 	at ihi.a(PG:19)
E/HttpOperation( 6601): 	... 14 more
E/EsSyncAdapterService( 6601): Sync failure
E/EsSyncAdapterService( 6601): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6601): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6601): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6601): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6601): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6601): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6601): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6601): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6601): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6601): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6601): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6601): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6601): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6601): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6601): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6601): 	... 10 more
E/EsSyncAdapterService( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6601): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6601): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6601): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6601): 	... 12 more
E/EsSyncAdapterService( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6601): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6601): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6601): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6601): 	... 14 more
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  902): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 65622, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
D/ResourcesManager( 1675): creating new AssetManager and set to /system/app/Books/Books.apk
V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecContentProvider2(  902): uri = 14 selection = getSealedState
D/SecContentProvider2(  902): mCursor = null
D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/GLSActivity( 1675): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1675): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1675): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1675): 	at android.os.Binder.execTransact(Binder.java:446)
D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/BooksAccountManager( 7349): Authentication error
E/BooksAccountManager( 7349): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7349): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7349): null auth token
I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
I/System.out( 7349): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 7349): (HTTPLog)-Static: isShipBuild true
I/System.out( 7349): (HTTPLog)-Thread-1212-457086525: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
I/qtaguid ( 7349): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7349, getuid(): 10082
D/SecContentProvider2(  902): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  902): mCursor = null
I/qtaguid ( 7349): Untagging socket 34
W/ApiaryClient( 7349): Error response from books API: {
W/ApiaryClient( 7349):  "error": {
W/ApiaryClient( 7349):   "errors": [
W/ApiaryClient( 7349):    {
W/ApiaryClient( 7349):     "domain": "global",
W/ApiaryClient( 7349):     "reason": "required",
W/ApiaryClient( 7349):     "message": "Login Required",
W/ApiaryClient( 7349):     "locationType": "header",
W/ApiaryClient( 7349):     "location": "Authorization"
W/ApiaryClient( 7349):    }
W/ApiaryClient( 7349):   ],
W/ApiaryClient( 7349):   "code": 401,
W/ApiaryClient( 7349):   "message": "Login Required"
W/ApiaryClient( 7349):  }
W/ApiaryClient( 7349): }
W/ApiaryClient( 7349): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7349): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7036289533068325534&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7349): Headers suppressed
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/AndroidRuntime( 7405): 
D/AndroidRuntime( 7405): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7405): CheckJNI is OFF
D/AndroidRuntime( 7405): setted country_code = Germany
D/AndroidRuntime( 7405): setted countryiso_code = DE
D/AndroidRuntime( 7405): setted sales_code = DBT
D/AndroidRuntime( 7405): readGMSProperty: start
D/AndroidRuntime( 7405): readGMSProperty: already setted!!
D/AndroidRuntime( 7405): readGMSProperty: end
D/AndroidRuntime( 7405): addProductProperty: start
E/SQLiteLog( 1675): (10) POSIX Error : 11 SQLite Error : 3850
E/AffinityControl( 7405): AffinityControl: registerfunction enter
D/AndroidRuntime( 7405): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  902): inState():  stateMachine is null !!
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/ResourcesManager(  902): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/ActivityManager(  902): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  902): mDVFSHelper.acquire()
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7428): MountEmulatedStorage()
E/Zygote  ( 7428): v2
I/libpersona( 7428): KNOX_SDCARD checking this for 10200
I/libpersona( 7428): KNOX_SDCARD not a persona
I/ActivityManager(  902): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7428 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7428): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7428): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/SELinux ( 7428): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 7405): Shutting down VM
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/TimaKeyStoreProvider( 7428): TimaSignature is unavailable
D/ActivityThread( 7428): Added TimaKeyStore provider
V/ActivityManager(  902): Display changed displayId=0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SQLiteSecureOpenHelper( 3567): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3567): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger(  251): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/8)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  251): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
D/ResourcesManager( 7428): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  902): uri = 14 selection = getSealedState
D/SecContentProvider2(  902): mCursor = null
D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
I/WebViewFactory( 7428): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7428): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/GLSActivity( 1675): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1675): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1675): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1675): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7349): Authentication error
E/BooksAccountManager( 7349): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7349): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7349): null auth token
I/qtaguid ( 7349): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7349, getuid(): 10082
I/qtaguid ( 7349): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7349, getuid(): 10082
I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
I/LibraryLoader( 7428): Loading: webviewchromium
I/LibraryLoader( 7428): Time to load native libraries: 4 ms (timestamps 6913-6917)
I/LibraryLoader( 7428): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7428): Binding Chromium to main looper Looper (main, tid 1) {326ec22f}
I/LibraryLoader( 7428): Expected native library version number "",actual native library version number ""
I/chromium( 7428): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7428): Initializing chromium process, renderers=0
W/art     ( 7428): Attempt to remove local handle scope entry from IRT, ignoring
I/qtaguid ( 7349): Untagging socket 34
W/ApiaryClient( 7349): Error response from books API: {
W/ApiaryClient( 7349):  "error": {
W/ApiaryClient( 7349):   "errors": [
W/ApiaryClient( 7349):    {
W/ApiaryClient( 7349):     "domain": "global",
W/ApiaryClient( 7349):     "reason": "required",
W/ApiaryClient( 7349):     "message": "Login Required",
W/ApiaryClient( 7349):     "locationType": "header",
W/ApiaryClient( 7349):     "location": "Authorization"
W/ApiaryClient( 7349):    }
W/ApiaryClient( 7349):   ],
W/ApiaryClient( 7349):   "code": 401,
W/ApiaryClient( 7349):   "message": "Login Required"
W/ApiaryClient( 7349):  }
W/ApiaryClient( 7349): }
W/ApiaryClient( 7349): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7349): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7036289533068325534&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7349): Headers suppressed
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/chromium( 7428): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7428): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7428): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
W/ActivityManager(  902): Activity pause timeout for ActivityRecord{2d9dc3de u0 com.test.thalitest/.MainActivity t18}
I/Adreno-EGL( 7428): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7428): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7428): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7428): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7428): Remote Branch: 
I/Adreno-EGL( 7428): Local Patches: 
I/Adreno-EGL( 7428): Reconstruct Branch: 
W/chromium( 7428): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7428): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7428): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7428): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7428): CordovaWebView is running on device made by: samsung
,W/art     ( 7428): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 7428): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 7428): performCreate Call secproduct feature valuefalse
,D/Activity( 7428): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7428): Render dirty regions requested: true
,D/ActivityManager(  902): post active user change for 0
,D/KnoxTimeoutHandler(  902): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  902): handleActiveUserChange for user 0
,E/SMD     (  287): DCD ON
,I/SurfaceFlinger(  251): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/StatusBarManagerService(  902): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/StatusBarManagerService(  902): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/OpenGLRenderer( 7428): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7428): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7428): Enabling debug mode 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/InputMethodManagerService(  902): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/ActivityManager(  902): mDVFSHelper.release()
,I/Timeline(  902): Timeline: Activity_windows_visible id: ActivityRecord{2d9dc3de u0 com.test.thalitest/.MainActivity t18} time:97785
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/IInputConnectionWrapper( 7428): showStatusIcon on inactive InputConnection
I/Timeline( 7428): Timeline: Activity_idle id: android.os.BinderProxy@233ef0be time:97801
,I/chromium( 7428): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7428): 
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1675): Explicit concurrent mark sweep GC freed 25139(1533KB) AllocSpace objects, 12(972KB) LOS objects, 40% free, 17MB/29MB, paused 881us total 80.375ms
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/JsMessageQueue( 7428): Set native->JS mode to OnlineEventsBridgeMode
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1675): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
D/SecContentProvider2(  902): mCursor = null
D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
W/GLSActivity( 1675): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1675): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1675): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1675): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/BooksAccountManager( 7349): Authentication error
E/BooksAccountManager( 7349): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7349): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7349): null auth token
,I/qtaguid ( 7349): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7349, getuid(): 10082
,I/qtaguid ( 7349): Untagging socket 34
W/ApiaryClient( 7349): Error response from books API: {
W/ApiaryClient( 7349):  "error": {
W/ApiaryClient( 7349):   "errors": [
W/ApiaryClient( 7349):    {
W/ApiaryClient( 7349):     "domain": "global",
W/ApiaryClient( 7349):     "reason": "required",
W/ApiaryClient( 7349):     "message": "Login Required",
W/ApiaryClient( 7349):     "locationType": "header",
W/ApiaryClient( 7349):     "location": "Authorization"
W/ApiaryClient( 7349):    }
W/ApiaryClient( 7349):   ],
W/ApiaryClient( 7349):   "code": 401,
W/ApiaryClient( 7349):   "message": "Login Required"
W/ApiaryClient( 7349):  }
W/ApiaryClient( 7349): }
,W/ApiaryClient( 7349): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7349): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7036289533068325534&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7349): Headers suppressed
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/jxcore_app_log( 7428): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359590400
,D/JX-Cordova( 7428): jxcore cordova android initializing
,D/SSRM:m  (  902): SIOP:: AP = 350, PST = 417, CUR = 300
,I/art     ( 7428): Background sticky concurrent mark sweep GC freed 43079(3MB) AllocSpace objects, 10(320KB) LOS objects, 15% free, 19MB/23MB, paused 7.168ms total 47.271ms
,E/BooksSync( 7349): Soft error
E/BooksSync( 7349): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7349): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7036289533068325534&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7349): Headers suppressed
E/BooksSync( 7349): 
E/BooksSync( 7349): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7349): Sync error
E/BooksSync( 7349): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7349): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7036289533068325534&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7349): Headers suppressed
E/BooksSync( 7349): 
E/BooksSync( 7349): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7349): Finished books sync
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  902): waitForAlarm result :4
,I/ActivityManager(  902): Killing 6545:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,D/SyncManager(  902): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 66148, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  902): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  902): mCursor = null
,W/libprocessgroup(  902): failed to open /acct/uid_1000/pid_6545/cgroup.procs: No such file or directory
,I/GAV2    ( 7349): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6632): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6632): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6632): [1] 5.onFinished: Scheduling replication attempt 2.
,W/jxcore-log( 7428): Initializing JXcore engine
,W/jxcore-log( 7428): JXcore engine is ready
,W/jxcore-log( 7428): Starting JXcore engine
,E/auditd  ( 2098): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  902): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  902): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7558): MountEmulatedStorage()
,E/Zygote  ( 7558): v2
I/libpersona( 7558): KNOX_SDCARD checking this for 1000
I/libpersona( 7558): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7558 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7558): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7558): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7558): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7558): TimaSignature is unavailable
,D/ActivityThread( 7558): Added TimaKeyStore provider
,W/jxcore-log( 7428): Platform android
W/jxcore-log( 7428): 
W/jxcore-log( 7428): Process ARCH arm
W/jxcore-log( 7428): 
,D/ResourcesManager( 7558): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7558):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7558):  SeDenialReceiver : File path = null
,I/ActivityManager(  902): Killing 6586:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  902): failed to open /acct/uid_1000/pid_6586/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD ON
,I/jxcore-log( 7428): JXcore Cordova bridge is ready!
I/jxcore-log( 7428): 
,W/jxcore-log( 7428): JXcore engine is started
,I/jxcore-log( 7428): Toggling radios to true
I/jxcore-log( 7428): 
,D/BluetoothAdapter( 7428): enable()
,D/BluetoothAdapter( 7428): enable(): BT is already enabled..!
,D/WifiService(  902): New client listening to asynchronous messages
,I/WifiManager( 7428): packageName : com.test.thalitest
,D/SecContentProvider(  902): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  902): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  902): mCursor = null
,D/WifiService(  902): setWifiEnabled: true pid=7428, uid=10200
E/WifiService(  902): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  902): Permission Denial: getCurrentUser() from pid=7428, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  902): Failed getting userId using ActivityManagerNative
W/WifiService(  902): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7428, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  902): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  902): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  902): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  902): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  902): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  902): name = wifi_on
I/WifiService(  902): disconnect: pid=7428, uid=10200
,I/wpa_supplicant( 1295): [wpa_supplicant_ctrl_iface_process] : DISCONNECT,
,I/jxcore-log( 7428): Radios toggled
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): My device name is: samsung-SM-G900F
I/jxcore-log( 7428): 
,I/wpa_supplicant( 1295): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1295): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1295): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1295): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  902): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1295): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1295): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1295): Disconnected - do not scan
I/wpa_supplicant( 1295): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine(  902): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  902): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  902): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  902): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  902): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  902): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  902): do suspend true
,D/WifiP2pService(  902): InactiveState{ what=143375 }
,D/WifiP2pService(  902): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  282): Clearing all IP addresses on wlan0
V/NativeCrypto( 1675): Read error: ssl=0xad242600: I/O error during system call, Connection timed out
V/NativeCrypto( 1675): SSL shutdown failed: ssl=0xad242600: I/O error during system call, Broken pipe
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): Validated
D/ConnectivityService(  902): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  902): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  902):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  902):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  902): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  902): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  902): calling update connectivity
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  902): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524290
,E/WifiStateMachine(  902): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  902): updateNetworkInfo()
,D/ConnectivityService(  902): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  902): updateNetworkInfo()
D/ConnectivityService(  902): ignoring duplicate network state non-change
,D/ConnectivityService(  902): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,I/WifiTrafficPoller(  902): evaluateTrafficStatsPolling
,E/WifiConfigStore(  902): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/CLocInfoService(  902): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  902): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1295): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1295): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1295): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1295): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 1295): First Scan Start
,I/wpa_supplicant( 1295): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  902): ConnectModeState: Network connection lost 
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/WifiStateMachine(  902): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  902): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  902): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/native  (  902): do suspend true
,D/WifiP2pService(  902): InactiveState{ what=143375 }
,D/WifiP2pService(  902): P2pEnabledState{ what=143375 }
,I/Hs20UtilService( 1304): Starting #6
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  282): Clearing all IP addresses on wlan0
,D/ConnectivityService(  902): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  902): calling update connectivity
,D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  902): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/EntConnectivity(  902): Not allowed due to - mEnabled false
D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524292
,D/Nat464Xlat(  902): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  902): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): Disconnected - quitting
,D/ConnectivityService(  902): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1453): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker(  902): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  902): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiStateMachine(  902): updateConfiguredNetworkExpiration - currTime: 1452688657507
,D/WifiStateMachine(  902): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine(  902): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  902): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  902): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  902): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  902): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  902): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  902): NetworkAgent: NetworkAgent channel lost
,I/WifiTrafficPoller(  902): evaluateTrafficStatsPolling
,E/WifiStateMachine(  902): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  902): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
I/CLocInfoService(  902): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  902): setDetailed state send new extra info"NG700"
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  902): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  902): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  902): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
,D/SmartBondingService(  902): getSBEnabled() enabled =false
,D/SmartBondingService(  902): getNetworkEnabled : wifi : true mobile : true
,V/NetworkStats(  902): updateIfacesLocked()
V/NetworkStats(  902): performPollLocked(flags=0x1)
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  902): UpdateStatsForKnox
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  902): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  902): mCursor = null
,D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1171): updateDataNetType()
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
,V/NetworkStats(  902): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
,V/NetworkStats(  902): performPollLocked() took 11ms
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
I/Hs20UtilService( 1304): Starting #7
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
I/Hs20UtilService( 1304): Message received 5007
,D/SecContentProvider2(  902): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  902): mCursor = null
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/NtpTrustedTime(  902): currentTimeMillis() cache hit
,D/NtpTrustedTime(  902): currentTimeMillis() cache hit
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  902): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  902): MasterInitialState.processMessage what=3
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  902): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
,I/CLocInfoService(  902): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  902): getNetworkEnabled : wifi : true mobile : true
,I/CLocInfoService(  902): CLoinfo wifi false
,I/ApplicationPolicy(  902): updateDataUsageMap
,D/accuweather( 2251): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7142): [#DCM#] [DCM_Performance] onReceive completed in time  1441 microsec. 
,I/DBG_DM  ( 3781): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/SystemBroadcastReceiver( 7142): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7142): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,I/DCMController( 7142): [#DCM#] setIsConnectedForExtractors 
,W/SLocation(  902): No Active Data Connection
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5359): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 6754): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6754): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6754): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6754): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6754): noConnectivity : true
,I/DBG_DM  ( 3781): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7628): MountEmulatedStorage()
,E/Zygote  ( 7628): v2
I/libpersona( 7628): KNOX_SDCARD checking this for 10002
I/libpersona( 7628): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7628 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  317): Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 286us total 16.124ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 267us total 8.073ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 263us total 8.695ms
,I/SELinux ( 7628): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7628): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7628): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7628): TimaSignature is unavailable
,D/ActivityThread( 7628): Added TimaKeyStore provider
,D/ResourcesManager( 7628): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  902): Killing 6717:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7647): MountEmulatedStorage()
E/Zygote  ( 7647): v2
I/libpersona( 7647): KNOX_SDCARD checking this for 1000
I/libpersona( 7647): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7647 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7647): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7647): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7647): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7647): TimaSignature is unavailable
,D/ActivityThread( 7647): Added TimaKeyStore provider
,W/libprocessgroup(  902): failed to open /acct/uid_10015/pid_6717/cgroup.procs: No such file or directory
,D/ResourcesManager( 7647): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7647): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7647): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/wpa_supplicant( 1295): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant( 1295): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1295): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1295): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1295): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  902): [1,452,688,658,514 ms] noteScanEnd no scan source
,E/WifiStateMachine(  902): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1fda05ff sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  902): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  902): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  902): setDetailed state send new extra info0x
D/SecContentProvider2(  902): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  902): mCursor = null
,I/CLocInfoService(  902): External Intent Received android.net.wifi.SCAN_RESULTS
,I/DIAGMON_AGENT( 7647): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7647): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7647): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7647): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/wpa_supplicant( 1295): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1295): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1295): Associated with C0.AA.48
,E/WifiStateMachine(  902): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  902): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  902): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  902): mCursor = null
,I/wpa_supplicant( 1295): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1295): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  902): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  902): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  902): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  902): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  902): mCursor = null
,I/wpa_supplicant( 1295): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1295): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1295): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  902): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  902): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 1295): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1295): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1295): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1295): Blacklist: Clear (temp) 
I/wpa_supplicant( 1295): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  902): Network connection established
,D/WifiNative-HAL(  902): callSECApiVoid - ID [50]
E/WifiStateMachine(  902): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  902): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7663 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 7663): MountEmulatedStorage()
E/Zygote  ( 7663): v2
I/libpersona( 7663): KNOX_SDCARD checking this for 10011
I/libpersona( 7663): KNOX_SDCARD not a persona
,I/CLocInfoService(  902): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  902): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService(  902): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  902): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  902): Got NetworkAgent Messenger
E/WifiStateMachine(  902): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  902): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  902): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  902): updateNetworkInfo()
,D/ConnectivityService(  902): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  902): NetworkAgent connected
,E/WifiStateMachine(  902): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  902): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  902): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  902): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  282): Setting iface cfg
,E/WifiStateMachine(  902): Start Dhcp Watchdog 2
,D/SecContentProvider2(  902): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  902): mCursor = null
,I/SELinux ( 7663): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SELinux ( 7663): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7663): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  902): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  902): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  902): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/TimaKeyStoreProvider( 7663): TimaSignature is unavailable
,D/ActivityThread( 7663): Added TimaKeyStore provider
,D/ResourcesManager( 7663): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  902): Killing 6735:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,I/FOTA_Client( 7663): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,E/WifiStateMachine(  902): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  902): do suspend false
,I/FOTA_Client( 7663): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/WifiP2pService(  902): InactiveState{ what=143375 }
,D/SecContentProvider2(  902): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService(  902): P2pEnabledState{ what=143375 }
D/SecContentProvider2(  902): mCursor = null
,I/FOTA_Client( 7663): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7663): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7663): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7680): MountEmulatedStorage()
,E/Zygote  ( 7680): v2
I/libpersona( 7680): KNOX_SDCARD checking this for 10019
I/libpersona( 7680): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7680 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  902): Killing 6503:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,I/SELinux ( 7680): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7680): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/libprocessgroup(  902): failed to open /acct/uid_10016/pid_6735/cgroup.procs: No such file or directory
,E/SELinux ( 7680): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7680): TimaSignature is unavailable
,D/ActivityThread( 7680): Added TimaKeyStore provider
,D/ResourcesManager( 7680): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7680): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7680): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452688658871
,I/KLMS-2.4.503: ( 7680): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7680): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7680): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  902): Killing 4715:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,W/libprocessgroup(  902): failed to open /acct/uid_10034/pid_6503/cgroup.procs: No such file or directory
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7695): MountEmulatedStorage()
I/libpersona( 7695): KNOX_SDCARD checking this for 10037
E/Zygote  ( 7695): v2
I/libpersona( 7695): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7695 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7695): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7695): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7695): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7695): TimaSignature is unavailable
,D/ActivityThread( 7695): Added TimaKeyStore provider
,D/ResourcesManager( 7695): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7695): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,W/libprocessgroup(  902): failed to open /acct/uid_10035/pid_4715/cgroup.procs: No such file or directory
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/dhcpcd  ( 7710): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7710): version 5.5.6 starting
,E/SPPClientService( 5223): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,E/dhcpcd  ( 7710): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/SA      ( 6792): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6792): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6792): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6792): [SLFUCHKMGR] constructor called
,I/SA      ( 6792): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6792): [OR] == isSIMCardReady false ==
,I/SA      ( 6792): [SCU] == networkStateCheck == false
I/SA      ( 6792): [OR] onReceive END
,E/SPPClientService( 5223): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/X       (  902): broadcastSiopLevelIntent:: currentSiopLevel = -1
,E/Zygote  ( 7717): MountEmulatedStorage()
,E/Zygote  ( 7717): v2
I/libpersona( 7717): KNOX_SDCARD checking this for 10071
I/libpersona( 7717): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7717 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/dhcpcd  ( 7710): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7710): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7710): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7710): bssid match
,I/dhcpcd  ( 7710): wlan0: rebinding lease of 192.168.1.135
I/SELinux ( 7717): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SystemBroadcastReceiver( 7142): [#DCM#] [DCM_Performance] onReceive completed in time  71 microsec. 
,I/SystemBroadcastReceiver( 7142): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7142): [#DCM#] onReceive action = EVENT_SIOP
I/SELinux ( 7717): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  902): Killing 6064:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
E/SELinux ( 7717): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ContentApp( 1221):  LEVEL : -1
,D/TimaKeyStoreProvider( 7717): TimaSignature is unavailable
,D/ActivityThread( 7717): Added TimaKeyStore provider
,D/ResourcesManager( 7717): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7717): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7717): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7717): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/dhcpcd  ( 7710): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,D/comsamsunglog( 7717): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7717): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7717): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7717): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7717): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7717): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7717): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7717): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  902): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  902): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  902): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  902): selectionArgs: false
D/SettingsProvider(  902): selectionArgs: 10071
D/SecContentProvider(  902): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  902): ret = -1
,W/libprocessgroup(  902): failed to open /acct/uid_10042/pid_6064/cgroup.procs: No such file or directory
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/dhcpcd  ( 7710): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  902): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  902): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  902): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/accuweather( 7717): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7717): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
D/accuweather( 7717): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7717): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7717): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7717): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7717): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7717): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7717): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7717): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7742): MountEmulatedStorage()
,E/Zygote  ( 7742): v2
I/libpersona( 7742): KNOX_SDCARD checking this for 1000
I/libpersona( 7742): KNOX_SDCARD not a persona
I/ActivityManager(  902): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7742 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  902): Killing 5713:com.android.mms/u0a50 (adj 15): bgCount ##41
,I/SELinux ( 7742): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/CountryDetector(  902): No listener is left
,I/SELinux ( 7742): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7742): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7742): TimaSignature is unavailable
,D/ActivityThread( 7742): Added TimaKeyStore provider
,D/ResourcesManager( 7742): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7742): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  902): failed to open /acct/uid_10050/pid_5713/cgroup.procs: No such file or directory
,I/KnoxUsageLogPro( 7742): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7742): premStatus:2
,I/KnoxUsageLogPro( 7742): isEulaShown : false
,I/KnoxUsageLogPro( 7742): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7772): MountEmulatedStorage()
E/Zygote  ( 7772): v2
I/libpersona( 7772): KNOX_SDCARD checking this for 10088
I/libpersona( 7772): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7772 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  902): Killing 6818:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 7772): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7772): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7772): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  902): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  902): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  902): do suspend true
,D/TimaKeyStoreProvider( 7772): TimaSignature is unavailable
,D/ActivityThread( 7772): Added TimaKeyStore provider
,D/WifiP2pService(  902): InactiveState{ what=143375 }
,D/WifiP2pService(  902): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  902): WifiStateMachine DHCP successful
,E/WifiStateMachine(  902): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  902): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  902): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
D/ResourcesManager( 7772): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/WifiStateMachine(  902): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiStateMachine(  902): Not connected state, yet.
E/WifiStateMachine(  902): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  902): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine(  902): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  902): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  902): callSECApiInt - ID [210]
E/WifiStateMachine(  902): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService(  902): updateNetworkInfo()
,D/ConnectivityService(  902): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  902): Adding iface wlan0 to network 503
,I/CLocInfoService(  902): External Intent Received android.net.wifi.STATE_CHANGE
D/WifiWatchdogStateMachine(  902): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  902): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  902): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  902): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  902): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  902): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  902): Now, connected state.
,E/WifiStateMachine(  902): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  902): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,E/WifiStateMachine(  902): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  902): evaluateTrafficStatsPolling
,I/CLocInfoService(  902): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  902): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine(  902): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  902): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  902): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/ConnectivityService(  902): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  902): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  902): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  282): QcRouteController
I/WifiTrafficPoller(  902): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  902): mBoosterFLAG : 0
,I/WifiTrafficPoller(  902): current booster mode : FullMode
D/WifiNative-HAL(  902): callSECApiVoid - ID [212]
I/CLocInfoService(  902): External Intent Received android.net.wifi.STATE_CHANGE
,W/libprocessgroup(  902): failed to open /acct/uid_10051/pid_6818/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,I/WifiStateMachine(  902): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,D/ConnectivityService(  902): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  902): requiresClat: netType=1, connected=false, hasIPv4Address=true
E/ConnectivityService(  902): updateNetworkInfo()
D/ConnectivityService(  902): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  902): updateNetworkInfo()
D/ConnectivityService(  902): calling update connectivity
D/ConnectivityService(  902): ignoring duplicate network state non-change
D/ConnectivityService(  902): ignoring duplicate network state non-change
D/ConnectivityService(  902): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  902): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  902): calling update connectivity
D/ConnectivityService(  902): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  902):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  902):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  902):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902): currentScore = 0, newScore = 60
D/ConnectivityService(  902):    accepting network in place of null
D/ConnectivityService(  902): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1453): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
E/CSLegacyTypeTracker(  902): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  902): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  902): Validated
,D/ConnectivityService(  902): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  902): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  902): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  902): calling update connectivity
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  902): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  902): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  902): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  902):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  902):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  902): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  902): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  902): calling update connectivity
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  902): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524290
D/SmartBondingService(  902): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  902): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
,V/NetworkStats(  902): updateIfacesLocked()
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
V/NetworkStats(  902): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  902): UpdateStatsForKnox
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  902): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524290
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
V/NetworkStats(  902): performPollLocked() took 4ms
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
V/NetworkStats(  902): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/NtpTrustedTime(  902): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/ActivityManager(  902): Killing 6840:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,D/Headlines( 5508): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5508): getCountryCode(): countryCode = DE
,D/Headlines( 5508): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5508): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5508): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5508): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5508): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5508): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5508): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7805): MountEmulatedStorage()
E/Zygote  ( 7805): v2
I/libpersona( 7805): KNOX_SDCARD checking this for 10128
I/libpersona( 7805): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7805 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  902): failed to open /acct/uid_10058/pid_6840/cgroup.procs: No such file or directory
,I/SELinux ( 7805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7805): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7805): TimaSignature is unavailable
,D/ActivityThread( 7805): Added TimaKeyStore provider
,D/ResourcesManager( 7805): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  250): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  250): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7805): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  250): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  250): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7805): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  250): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  250): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7805): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  250): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  250): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7805): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,I/WebViewFactory( 7805): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7805): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7805): Loading: webviewchromium
,I/LibraryLoader( 7805): Time to load native libraries: 5 ms (timestamps 3684-3689)
,I/LibraryLoader( 7805): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7805): Binding Chromium to main looper Looper (main, tid 1) {3525c20b}
,I/LibraryLoader( 7805): Expected native library version number "",actual native library version number ""
,I/chromium( 7805): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7805): Initializing chromium process, renderers=0
,W/art     ( 7805): Attempt to remove local handle scope entry from IRT, ignoring
,I/PowerManagerService(  902): [PWL] Off : 15s ago
,I/PowerManagerService(  902): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  902): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  902): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=902, ws=null) (elapsedTime=2466)
,W/chromium( 7805): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,W/AudioManagerAndroid( 7805): Requires BLUETOOTH permission
,I/chromium( 7805): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium( 7805): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/Adreno-EGL( 7805): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7805): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7805): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7805): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7805): Remote Branch: 
I/Adreno-EGL( 7805): Local Patches: 
I/Adreno-EGL( 7805): Reconstruct Branch: 
,D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  902): MasterInitialState.processMessage what=3
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  902): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  902): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  902): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  902): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
,I/CLocInfoService(  902): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  902): CLocinfo wifi true 
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  902): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2251): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3781): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3781): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2169): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2169): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,I/SystemBroadcastReceiver( 7142): [#DCM#] [DCM_Performance] onReceive completed in time  68 microsec. 
I/SystemBroadcastReceiver( 7142): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7142): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7142): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DatabaseRebuilderTask( 7142): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PackageManager(  902): [MSG] SEND_PENDING_BROADCAST
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5359): type=WIFI subType= reason=null isConnected=true
,I/FrameworkService( 7142): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7142): [#DCM#] onCreate FrameworkService end 
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DCMConfig( 7142): [#DCM#] getSuccessState = true
,I/FrameworkService( 7142): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
,D/ResourcesManager(  902): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/IntentHandler( 7142): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/SystemUtils( 7142): [#DCM#] LM: false,AM:642486272
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
E/Watchdog(  902): !@Sync 3
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/InputReader(  902): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/RegisteredServicesCache( 1447): empty dynamic service
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,I/art     (  902): Explicit concurrent mark sweep GC freed 80584(4MB) AllocSpace objects, 12(517KB) LOS objects, 30% free, 36MB/52MB, paused 1.664ms total 164.487ms
,D/SecContentProvider2(  902): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  902): mCursor = null
,I/DCMThreadPoolExecutor( 7142): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7142): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@2596c4e9 is submitted
,I/FrameworkService( 7142): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 180640 mirosec. 
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/NSApplication( 7805): Starting up...
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/SecContentProvider2(  902): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  902): mCursor = null
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,D/BackupManagerService(  902): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/Zygote  ( 7864): MountEmulatedStorage()
E/Zygote  ( 7864): v2
I/libpersona( 7864): KNOX_SDCARD checking this for 10138
I/libpersona( 7864): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7864 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7864): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/SELinux ( 7864): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7864): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/TimaKeyStoreProvider( 7864): TimaSignature is unavailable
D/ActivityThread( 7864): Added TimaKeyStore provider
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7864): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/ResourcesManager( 7864): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7864): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7864): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ConnectivityService(  902): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/QuickConnect( 7864): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7864): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/QuickConnect( 7864): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager(  902): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  902): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  902): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 7879): MountEmulatedStorage()
E/Zygote  ( 7879): v2
I/libpersona( 7879): KNOX_SDCARD checking this for 10163
I/libpersona( 7879): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7879 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager(  902): Killing 6250:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,I/SELinux ( 7879): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7879): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7879): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  902): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/TimaKeyStoreProvider( 7879): TimaSignature is unavailable
,D/ActivityThread( 7879): Added TimaKeyStore provider
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 7879): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7879): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7879): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7879): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7879): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/libprocessgroup(  902): failed to open /acct/uid_1000/pid_6250/cgroup.procs: No such file or directory
,D/RCPManagerService(  902): exchangeData() failure , invalid userId
,D/RCPManagerService(  902): exchangeData() failure , invalid userId
,D/RCPManagerService(  902): exchangeData() failure , invalid userId
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  902): exchangeData() failure , invalid userId
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,E/Zygote  ( 7902): MountEmulatedStorage()
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
E/Zygote  ( 7902): v2
I/libpersona( 7902): KNOX_SDCARD checking this for 10078
I/libpersona( 7902): KNOX_SDCARD not a persona
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,I/ActivityManager(  902): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7902 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,I/art     (  317): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 273us total 16.738ms
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 8.009ms
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 7.684ms
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,I/SELinux ( 7902): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
V/BitmapFactory( 7879): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
I/SELinux ( 7902): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7902): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  902): exchangeData() failure , invalid userId
,D/RCPManagerService(  902): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 7902): TimaSignature is unavailable
,D/ActivityThread( 7902): Added TimaKeyStore provider
,I/ActivityManager(  902): Killing 6861:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7558): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7558): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7558): StateMachine : Current State = 1
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7558): StateMachine : Changed Current State = 1
,D/ResourcesManager( 7902): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,I/ActivityManager(  902): Killing 6913:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,D/com.peel.receiver.ConnectivityActionReceiver( 5611): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 5611): 
D/com.peel.receiver.ConnectivityActionReceiver( 5611): 
D/com.peel.receiver.ConnectivityActionReceiver( 5611): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5611): 
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 5611): 
D/com.peel.receiver.ConnectivityActionReceiver( 5611): 
D/com.peel.receiver.ConnectivityActionReceiver( 5611):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5611): 
D/com.peel.receiver.ConnectivityActionReceiver( 5611): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5611): 
D/com.peel.receiver.ConnectivityActionReceiver( 5611): 
D/com.peel.receiver.ConnectivityActionReceiver( 5611): last run: 1452672209054 -- System.currentTimeMillis()-last_run: 16451805
,D/com.peel.receiver.ConnectivityActionReceiver( 5611): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5611): ... skip last_72_check
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 7902): onCreate
,D/BadgeProvider( 7902): DatabaseHelper
,E/Zygote  ( 7918): MountEmulatedStorage()
E/Zygote  ( 7918): v2
I/libpersona( 7918): KNOX_SDCARD checking this for 10178
I/libpersona( 7918): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7918 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7918): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7918): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7918): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 7902): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 7918): TimaSignature is unavailable
,D/ActivityThread( 7918): Added TimaKeyStore provider
,D/BadgeProvider( 7902): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7902): sendNotify, [notify] : null
D/BadgeProvider( 7902): update, [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1474): reloadBadges entered.
D/BadgeProvider( 7902): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7902): update, [UpdateCount] : 1
,W/ActivityManager(  902): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ResourcesManager( 7918): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  902): Killing 6893:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2491): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2491): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  902): failed to open /acct/uid_10033/pid_6913/cgroup.procs: No such file or directory
,W/libprocessgroup(  902): failed to open /acct/uid_10098/pid_6861/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 7119): notifyNetworkActivated
I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
,D/SecContentProvider2(  902): mCursor = null
D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2491): [AccountUtils] Account not ready
W/Kids    ( 2491): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2491): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2491): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2491): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2491): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2491): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2491): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2491): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2491): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2491): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2491): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2491): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/ContextImpl( 7119): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  902): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/libprocessgroup(  902): failed to open /acct/uid_10099/pid_6893/cgroup.procs: No such file or directory
,D/hcjo    ( 7119): AutoUpdateManager:IDLE:execute
,I/Hs20UtilService( 1304): Starting #8
,I/Hs20UtilService( 1304): Message received 5007
D/InitializeManagerStateMachine( 7119): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7119): exit::IDLE
D/InitializeManagerStateMachine( 7119): entry::NETWORK_CHECK
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7119): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7119): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7119): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7119): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7119): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7119): entry::SUCCESS
D/hcjo    ( 7119): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/hcjo    ( 7119): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7119): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7119): exit::SUCCESS
D/InitializeManagerStateMachine( 7119): entry::IDLE
,E/TranscodeReceiver( 7202): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/TranscodeReceiver( 7202):  SIOP_LEVEL: -1
,I/Hs20UtilService( 1304): Starting #9
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1304): Starting #10
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1304): Message received 5007
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1304): Starting #11
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  902): callSECApi what=220
D/WifiStateMachine(  902): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 6754): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6754): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6754): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6754): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7647): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7647): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SurfaceFlinger(  251): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/PowerManagerService(  902): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=902
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/FOTA_Client( 7663): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7663): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7663): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7663): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7663): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7680): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7680): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452688661371
,I/KLMS-2.4.503: ( 7680): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7680): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7680): StateImplV2(): networkChangeListener().START
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/KLMS-2.4.503: ( 7680): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7680): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7695): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  902): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  902): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  902): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  902): identical MTU - not setting
D/ConnectivityService(  902): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  902): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
V/        (  282): QcRouteController
,E/WifiStateMachine(  902): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/SmartBondingService(  902): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  902): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
D/SmartBondingService(  902): getSBEnabled() enabled =false
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/        (  282): QcRouteController
,W/NetworkManagementService(  902): route cmd failed: 
W/NetworkManagementService(  902): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  902): '
W/NetworkManagementService(  902): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  902): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  902): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  902): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  902): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  902): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  902): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  902): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  902): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  902): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  902): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  902): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  902): calling update connectivity
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  902): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  902): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  902): calling update connectivity
D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524295
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  902):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  902): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524295
E/SPPClientService( 5223): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6792): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6792): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6792): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6792): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6792): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6792): [SCU] == networkStateCheck == true
I/SA      ( 6792): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6792): isChinaCountryCode : false
I/SA      ( 6792): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6792): [OR] == networkStateCheck true ==
,I/SA      ( 6792): [OR] GetMyCountryZoneTask
,I/SA      ( 6792): [OR] onReceive END
,I/SA      ( 6792): [SRS] prepareGetMyCountryZone
,I/SA      ( 6792): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6792): [SSP] query invoked
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 7717): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7717): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 6792): [TPMU] GetMccFromDB : null
I/SA      ( 6792): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6792): [TPM] isNoProxy(default) : true
I/KnoxUsageLogPro( 7742): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7742): premStatus:2
,I/KnoxUsageLogPro( 7742): isEulaShown : false
I/KnoxUsageLogPro( 7742): KnoxUsageReceiver onReceive : not Processible, just return
,E/File    ( 6792): fail readDirectory() errno=2
,D/Headlines( 5508): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5508): getCountryCode(): countryCode = DE
,D/Headlines( 5508): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/HeadlinesCardManager( 5508): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5508): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5508): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5508): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5508): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5508): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7864): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7864): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7864): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/RCPManagerService(  902): exchangeData() failure , invalid userId
,D/RCPManagerService(  902): exchangeData() failure , invalid userId
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7558): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7558): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7558): StateMachine : Current State = 1
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7558): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5611): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 5611): 
D/com.peel.receiver.ConnectivityActionReceiver( 5611): 
D/com.peel.receiver.ConnectivityActionReceiver( 5611): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5611): 
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5611): 
D/com.peel.receiver.ConnectivityActionReceiver( 5611): 
D/com.peel.receiver.ConnectivityActionReceiver( 5611):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5611): 
D/com.peel.receiver.ConnectivityActionReceiver( 5611): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5611): 
D/com.peel.receiver.ConnectivityActionReceiver( 5611): 
D/com.peel.receiver.ConnectivityActionReceiver( 5611): last run: 1452672209054 -- System.currentTimeMillis()-last_run: 16452484
D/com.peel.receiver.ConnectivityActionReceiver( 5611): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5611): ... skip last_72_check
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2491): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7119): AutoUpdateManager:IDLE:execute
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
D/InitializeManagerStateMachine( 7119): execute::IDLE:EXECUTE
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
D/InitializeManagerStateMachine( 7119): exit::IDLE
D/InitializeManagerStateMachine( 7119): entry::NETWORK_CHECK
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7119): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7119): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7119): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7119): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7119): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7119): entry::SUCCESS
D/hcjo    ( 7119): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7951): MountEmulatedStorage()
,E/Zygote  ( 7951): v2
I/libpersona( 7951): KNOX_SDCARD checking this for 10034
I/libpersona( 7951): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7951 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/hcjo    ( 7119): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7119): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/SELinux ( 7951): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7119): exit::SUCCESS
D/InitializeManagerStateMachine( 7119): entry::IDLE
I/SELinux ( 7951): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7951): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 7951): TimaSignature is unavailable
,D/ActivityThread( 7951): Added TimaKeyStore provider
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
D/SecContentProvider2(  902): mCursor = null
,D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2491): [AccountUtils] Account not ready
W/Kids    ( 2491): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2491): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2491): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2491): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2491): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2491): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2491): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2491): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2491): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2491): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2491): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2491): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,I/FeatureConfig( 7951): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7951): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 7951): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7951): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7951): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7951): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7951): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7951): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7951): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7968): MountEmulatedStorage()
I/libpersona( 7968): KNOX_SDCARD checking this for 10035
E/Zygote  ( 7968): v2
I/libpersona( 7968): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=7968 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  902): Killing 6950:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,I/SELinux ( 7968): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7968): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7968): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7968): TimaSignature is unavailable
,D/ActivityThread( 7968): Added TimaKeyStore provider
,W/libprocessgroup(  902): failed to open /acct/uid_10003/pid_6950/cgroup.procs: No such file or directory
,D/ResourcesManager( 7968): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/SA      ( 6792): [RC New] Execute method=[GET] start
,I/SA      ( 6792): [RC New] Security=[true]
,I/System.out( 6792): Thread-1100(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6792): Thread-1100(ApacheHTTPLog):isShipBuild true
,I/System.out( 6792): Thread-1100(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7990): MountEmulatedStorage()
,E/Zygote  ( 7990): v2
I/libpersona( 7990): KNOX_SDCARD checking this for 10017
I/libpersona( 7990): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=7990 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/SELinux ( 7990): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7990): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7990): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7990): TimaSignature is unavailable
,D/ActivityThread( 7990): Added TimaKeyStore provider
,D/ResourcesManager( 7990): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/BluetoothManager( 7968): getConnectedDevices
,D/-----SIC-----( 7968): ------------------skip uv
,D/-----SIC-----( 7968): ------------------skip SPO2
D/-----SIC-----( 7968): ------------------skip TGH
,I/SecureStorage( 7990): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  338): [INFO]: SPID(0x00000005)Credentials: uid 10017, gid 10017, pid 7990
I/SecureStorage(  338): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,E/Vold    (  250): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    (  250): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7968): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    (  250): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    (  250): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7968): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer( 7968): decode(33, 19359868, 4230)
,V/MediaPlayerService(  293): decode(30, 19359868, 4230)
,V/MediaPlayerService(  293): player type = 3
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
,V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19359868, 4230)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xb061b470, 8, 0, 0)
V/AudioCache(  293): ignored
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
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
,V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthServiceInstalled() : HealthService is Installed.
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
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
,I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  293): mAudioTrackVector clear
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
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
,V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 7968): decode(35, 19213040, 15440)
,V/MediaPlayerService(  293): decode(30, 19213040, 15440)
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
I/ActivityManager(  902): Killing 6964:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19213040, 15440)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 8, 0, 0)
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
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 1, 0, 0)
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
I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
,I/AudioPlayer(  293): First fillBuffer call!!
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
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
,V/MediaPlayer( 7968): decode(36, 19257568, 9226)
V/MediaPlayerService(  293): decode(30, 19257568, 9226)
E/DatabaseUtils(  902): Writing exception to parcel
E/DatabaseUtils(  902): java.lang.NullPointerException: key == null
E/DatabaseUtils(  902): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  902): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  902): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  902): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  902): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  902): 	at android.os.Binder.execTransact(Binder.java:446)
V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
I/ActivityManager(  902): Killing 6976:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19257568, 9226)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 8, 0, 0)
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
,I/UpdateIcingCorporaServi( 1578): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
D/AdaptiveEventManager( 1171): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1171): M updateContainers()
D/AdaptiveEventContainerSmall( 1171): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1171): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1171): pedoEvent == null
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 1, 0, 0)
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
V/AudioCache(  293): notify(0xb0924b50, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
,I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,E/Zygote  ( 8040): MountEmulatedStorage()
I/libpersona( 8040): KNOX_SDCARD checking this for 10075
E/Zygote  ( 8040): v2
I/libpersona( 8040): KNOX_SDCARD not a persona
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,I/ActivityManager(  902): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8040 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x76, OMX_CommandStateSet, OMX_StateIdle)
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
,V/MediaPlayer( 7968): decode(37, 19364180, 4890)
,I/SELinux ( 8040): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/MediaPlayerService(  293): decode(30, 19364180, 4890)
,D/AdaptiveEventManager( 1171): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
,D/AdaptiveEventManager( 1171): M updateContainers()
I/SELinux ( 8040): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/AdaptiveEventContainerSmall( 1171): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1171): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1171): pedoEvent == null
,E/SELinux ( 8040): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/MediaPlayerService(  293): player type = 3
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
V/StagefrightPlayer(  293): setDataSource(30, 19364180, 4890)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 8, 0, 0)
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
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,W/libprocessgroup(  902): failed to open /acct/uid_10020/pid_6964/cgroup.procs: No such file or directory
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 1, 0, 0)
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
V/AudioCache(  293): notify(0xb04fc420, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
,V/MediaPlayerService(  293): wait for playback complete
,I/AudioPlayer(  293): First fillBuffer call!!
,I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
,E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,D/TimaKeyStoreProvider( 8040): TimaSignature is unavailable
,D/ActivityThread( 8040): Added TimaKeyStore provider
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x77, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 7968): decode(38, 19290344, 17329)
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
V/AudioCache(  293): notify(0xafa09290, 8, 0, 0)
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
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xafa09290, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa09290, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa09290, 1, 0, 0)
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
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa09290, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa09290, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa09290, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa09290, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
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
V/StagefrightPlayer(  293): ~StagefrightPlayer
,V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
,V/AwesomePlayer(  293): reset_l()
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 7968): decode(39, 19190536, 6644)
V/MediaPlayerService(  293): decode(30, 19190536, 6644)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
D/ResourcesManager( 8040): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
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
V/AudioCache(  293): notify(0xb1a0b060, 8, 0, 0)
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
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb1a0b060, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb1a0b060, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb1a0b060, 1, 0, 0)
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
V/AudioCache(  293): notify(0xb1a0b060, 6, 0, 0)
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
,V/MediaPlayerService(  293): wait for playback complete
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb1a0b060, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb1a0b060, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
,V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb1a0b060, 8, 0, 0)
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
V/MediaPlayer( 7968): decode(40, 19266876, 23389)
V/MediaPlayerService(  293): decode(30, 19266876, 23389)
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
V/StagefrightPlayer(  293): setDataSource(30, 19266876, 23389)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
D/FileShare-Server( 8040): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
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
V/AudioCache(  293): notify(0xb061b470, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 1, 0, 0)
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
V/AudioCache(  293): notify(0xb061b470, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
,I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,W/libprocessgroup(  902): failed to open /acct/uid_1000/pid_6976/cgroup.procs: No such file or directory
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
E/Zygote  ( 8071): MountEmulatedStorage()
E/Zygote  ( 8071): v2
I/libpersona( 8071): KNOX_SDCARD checking this for 1000
I/libpersona( 8071): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8071 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  902): Killing 7005:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,I/UpdateIcingCorporaServi( 1578): UpdateCorporaTask done [took 155 ms] updated apps [took 155 ms] 
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
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
V/StagefrightPlayer(  293): ~StagefrightPlayer
,V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 7968): decode(41, 19156232, 8154)
,I/SELinux ( 8071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
V/MediaPlayerService(  293): decode(30, 19156232, 8154)
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
V/StagefrightPlayer(  293): setDataSource(30, 19156232, 8154)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
I/SELinux ( 8071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8071): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
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
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 7, 0, 0)
V/AudioCache(  293): ignored
D/TimaKeyStoreProvider( 8071): TimaSignature is unavailable
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
D/ActivityThread( 8071): Added TimaKeyStore provider
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 8, 0, 0)
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
I/AudioPlayer(  293): reset out
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
,V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 7968): decode(42, 19129712, 4804)
V/MediaPlayerService(  293): decode(30, 19129712, 4804)
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
V/StagefrightPlayer(  293): setDataSource(30, 19129712, 4804)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
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
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/ResourcesManager( 8071): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
I/AudioPlayer(  293): First fillBuffer call!!
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 8, 0, 0)
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
I/AudioPlayer(  293): reset out
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
V/MediaPlayer( 7968): decode(43, 19099164, 9400)
V/MediaPlayerService(  293): decode(30, 19099164, 9400)
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
V/StagefrightPlayer(  293): setDataSource(30, 19099164, 9400)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
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
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
V/MediaPlayer( 7968): decode(49, 19172584, 4112)
V/MediaPlayerService(  293): decode(35, 19172584, 4112)
V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
W/libprocessgroup(  902): failed to open /acct/uid_10112/pid_7005/cgroup.procs: No such file or directory
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
V/AudioCache(  293): notify(0xafa09290, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(36) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector,
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 811298076, value : 198833648
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 811298076, value : 198833648
I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
I/WifiStateMachine(  902): REQUEST_POWER_SAVE_ON
I/AudioPlayer(  293): reset out
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
V/MediaPlayer( 7968): decode(44, 19307764, 52024)
V/MediaPlayerService(  293): decode(30, 19307764, 52024)
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
V/AudioCache(  293): notify(0xb1a0b060, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
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
V/AudioPolicyManager(  293): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
V/AudioCache(  293): notify(0xafa09290, 200, 973, 0)
V/AudioCache(  293): ignored
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa09290, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa09290, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa09290, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa09290, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa09290, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xafa09290, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb1a0b060, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb1a0b060, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb1a0b060, 1, 0, 0)
V/AudioCache(  293): prepared
I/AudioPlayer(  293): reset out
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
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor,
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
V/AwesomePlayer(  293): reset_l(),
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(48000, 2, 0x0, 1, 0)
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb1a0b060, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
D/ShortcutReceiver( 8071):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,E/WifiStateMachine(  902): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/PackageBroadcastService( 2491): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb1a0b060, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb1a0b060, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
,V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb1a0b060, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  293): mAudioTrackVector clear
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
,I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
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
D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthServiceInstalled() : HealthService is Installed.
V/MediaPlayer( 7968): decode(45, 19172584, 4112)
,V/MediaPlayerService(  293): decode(30, 19172584, 4112)
V/MediaPlayerService(  293): player type = 3
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
V/StagefrightPlayer(  293): setDataSource(30, 19172584, 4112)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 8, 0, 0)
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
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/PeopleContactsSync( 2491): CP2 sync disabled
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
,V/MediaPlayerService(  293): wait for playback complete
,I/AudioPlayer(  293): First fillBuffer call!!
,I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b470, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
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
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
,V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 7968): decode(46, 19235660, 21825)
V/MediaPlayerService(  293): decode(30, 19235660, 21825)
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
V/AwesomePlayer(  293): mSecMediaClock clear
,V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19235660, 21825)
V/AwesomePlayer(  293): reset_l()
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 8, 0, 0)
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
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 5, 0, 0)
,V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 1, 0, 0)
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
V/AudioCache(  293): notify(0xb061b510, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
,E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/SA      ( 6792): [RC New] [v2liruge] api execute + 806
,I/SA      ( 6792): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 6792): AsyncTask #1 calls detatch()
,I/SA      ( 6792): [ODM] saveOpenData( GEO_IP, PL )
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb061b510, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/ActivityManager(  902): Killing 7023:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 7968): decode(47, 19134596, 21552)
V/MediaPlayerService(  293): decode(30, 19134596, 21552)
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
V/StagefrightPlayer(  293): setDataSource(30, 19134596, 21552)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 8, 0, 0)
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
,I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
,I/SA      ( 6792): [OCP] update openData : PL
,V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
,I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/SA      ( 6792): [TPMU] getNetworkMcc : 
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
E/SMD     (  287): DCD ON
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 1, 0, 0)
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
V/AudioCache(  293): notify(0xb0924b50, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 4292761, value : -2137358184
,E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 4292761, value : -2137358184
I/SA      ( 6792): [SCU] saveMccToPreferece Start
I/SA      ( 6792): [SCU] RegionMCC : 260
I/SA      ( 6792): [SSP] query invoked
,I/SA      ( 6792): [TPMU] GetMccFromDB : null
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
,V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
,V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
,V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0924b50, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
,I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/SA      ( 6792): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6792): [SCU] saveMccToPreferece End
,I/SA      ( 6792): [RC New] executeRequest [v2liruge] end. 902
I/SA      ( 6792): [RC New] Execute end
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
V/MediaPlayer( 7968): decode(48, 19228560, 7017)
V/MediaPlayerService(  293): decode(30, 19228560, 7017)
,I/SA      ( 6792): [OR] GetMyCountryZoneTask mcc = 260
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
V/StagefrightPlayer(  293): setDataSource(30, 19228560, 7017)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/SA      ( 6792): [OR] GetMyCountryZoneTask Success
V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
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
,I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
,V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 5, 0, 0)
V/AudioCache(  293): ignored
,V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 1, 0, 0)
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
V/AudioCache(  293): notify(0xb04fc420, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
,I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 2, 0, 0)
,V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb04fc420, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
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
,I/SecureStorage(  338): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  338): [INFO]: SPID(0x00000005)PID: 7990, TID: 8002
,W/libprocessgroup(  902): failed to open /acct/uid_10118/pid_7023/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7710): wlan0: sending IPv6 Router Solicitation
,I/SecureStorage( 7990): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 7990): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,I/SecSQLiteOpenHelper( 7968): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper( 7968): getDatabaseLocked(b,b,pwd)...
,I/SecSQLiteOpenHelper( 7968): Open platform.db in secure mode
,D/SecSQLiteDatabase( 7968): Android Version: 5.0
,D/SecSQLiteDatabase( 7968): Load library secsqlite.so for Android 5.0
,I/SecSQLiteDatabase( 7968): openSecureDatabase...
,I/SecSQLiteDatabase( 7968): private openSecureDatabase...
,I/SecSQLiteConnectionPool( 7968): OpenSecure
I/SecSQLiteConnectionPool( 7968): OpenSecure with password
I/SecSQLiteConnectionPool( 7968): openSecureConnectionLocked
,I/SecSQLiteDatabase( 7968): ...private openSecureDatabase
I/SecSQLiteDatabase( 7968): ...openSecureDatabase
,I/SecSQLiteOpenHelper( 7968): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper( 7968): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7968): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/System.err( 7968): java.lang.NumberFormatException: Invalid int: "null"
,W/System.err( 7968): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err( 7968): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 7968): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 7968): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:449)
W/System.err( 7968): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1173)
W/System.err( 7968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7968): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7968): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/AlarmManager(  902): waitForAlarm result :4
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4313, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  902): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  902): stay LED for fully charged
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1675): Connected
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1675): Message class com.google.f.a.a.p
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GCM     ( 2491): Message from null null
,E/GCM     ( 2491): Dropping message from null
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 7428): Test app app.js loaded
I/jxcore-log( 7428): 
,I/chromium( 7428): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7428): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/SurfaceFlinger(  251): id=16 Removed Toast (8/9)
,I/SurfaceFlinger(  251): id=16 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/PowerManagerService(  902): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 902) eventTime = 108561
,D/PowerManagerService(  902): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=902 (0x0)
,D/PowerManagerService(  902): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=902, ws=WorkSource{10059}) (elapsedTime=3520)
,I/GAV4    ( 7805): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/SSRM:m  (  902): SIOP:: AP = 410, PST = 416, CUR = 300
,W/ProcessCpuTracker(  902): Skipping unknown process pid 8152
,E/SMD     (  287): DCD ON
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6754): mConnectivityHandler : connected
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6754): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6754): ================================================
,I/CSTORAGE( 6754):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
,I/CSTORAGE( 6754): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6754): [GetString-S]
,E/art     ( 6754): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6754): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6754): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6754): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6754): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6754): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6754): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7710): wlan0: sending IPv6 Router Solicitation
,I/GAV3    ( 7968): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  287): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/dhcpcd  ( 7710): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7710): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine( 7119): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7119): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7119): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7119): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  ( 7119): RestApi Request Add : 2307
,E/File    ( 7119): fail readDirectory() errno=2
,E/SMD     (  287): DCD ON
,D/PreloadUpdateManagerStateMachine( 7119): execute::CHECK_TIMEOUT_FOR_UPDATE:EXECUTE
,I/System.out( 7119): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 7119): (HTTPLog)-Static: isShipBuild true
,I/System.out( 7119): (HTTPLog)-Thread-1175-640170016: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/qtaguid ( 7119): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 7119, getuid(): 10040
,I/qtaguid ( 7119): Untagging socket 26
,D/hcjo    ( 7119): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 7119): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 7119): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7119): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7119): entry::REQ_UPDATE_CHECK
,I/Volley  ( 7119): RestApi Request Add : 2315
,I/qtaguid ( 7119): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 7119, getuid(): 10040
,I/qtaguid ( 7119): Untagging socket -1
,I/qtaguid ( 7119): Failed write_ctrl(u -1) res=-1 errno=9
,I/qtaguid ( 7119): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger( 7119): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 7119): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,D/PreloadUpdateManagerStateMachine( 7119): exit::REQ_UPDATE_CHECK
,D/PreloadUpdateManagerStateMachine( 7119): entry::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine( 7119): exit::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine( 7119): entry::FINISH
,D/PreloadUpdateManagerStateMachine( 7119): exit::FINISH
,D/PreloadUpdateManagerStateMachine( 7119): entry::IDLE
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/FactoryTest( 6473): Not factory mode
,D/FactoryTest( 6473): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6473): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6473): still no open session command from host, so toast
,W/ContextImpl( 6473): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6473): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6473): Timeline: Activity_launch_request id:com.android.settings time:117693
,E/PersonaManagerService(  902): inState():  stateMachine is null !!
,V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  902): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  902): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/MTPRx   ( 6473): started activity for popup
,I/SQLiteSecureOpenHelper( 3567): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3567): getDatabaseLocked(b,b,pwd)...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 1
,D/ResourcesManager( 6473): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6473): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6473): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6473): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6473): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6473): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6473): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6473): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/InputMethodManagerService(  902): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  902): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2b1c9ba8 attribute=null, token = android.os.BinderProxy@3600b8b5
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png,
V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6473): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6473): dev.kiessupport is : TRUE
,D/Activity( 6473): performCreate Call secproduct feature valuefalse
,D/Activity( 6473): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ActivityManager(  902): post active user change for 0
D/KnoxTimeoutHandler(  902): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  902): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/Timeline( 7428): Timeline: Activity_idle id: android.os.BinderProxy@233ef0be time:118307
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 30s ago
,D/SSRM:m  (  902): SIOP:: AP = 360, PST = 410, CUR = 300
,I/ActivityManager(  902): Waited long enough for: ServiceRecord{2edb020a u0 com.samsung.dcm/.framework.FrameworkService}
,V/AlarmManager(  902): waitForAlarm result :4
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  902): stay LED for fully charged
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager(  902): Waited long enough for: ServiceRecord{3600b430 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6632): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6632): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6632): [1] 5.onFinished: Scheduling replication attempt 3.
,W/ActivityManager(  902): mDVFSHelper.release()
,I/art     (  902): Explicit concurrent mark sweep GC freed 58788(3MB) AllocSpace objects, 8(258KB) LOS objects, 30% free, 36MB/52MB, paused 5.047ms total 362.620ms
,E/SMD     (  287): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,V/AlarmManager(  902): waitForAlarm result :8
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,V/AlarmManager(  902): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  902): SIOP:: AP = 330, PST = 397, CUR = 300
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  902): !@Sync 4
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/PowerManagerService(  902): [PWL] Off : 50s ago,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:m  (  902): SIOP:: AP = 320, PST = 382, CUR = 300
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,V/AlarmManager(  902): waitForAlarm result :4
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  902): stay LED for fully charged
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6632): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6632): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6632): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  902): SIOP:: AP = 310, PST = 365, CUR = 300
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:m  (  902): SIOP:: AP = 310, PST = 351, CUR = 300
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,V/AlarmManager(  902): waitForAlarm result :4
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  902): stay LED for fully charged
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager(  902): waitForAlarm result :4
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1675): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
,D/SecContentProvider2(  902): mCursor = null
,D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6601): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6601): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6601): 	at kfv.a(PG:65)
E/HttpOperation( 6601): 	at kff.u(PG:385)
E/HttpOperation( 6601): 	at kfb.a(PG:29)
E/HttpOperation( 6601): 	at kff.l(PG:132)
E/HttpOperation( 6601): 	at dsf.a(PG:807)
E/HttpOperation( 6601): 	at fhk.a(PG:1126)
E/HttpOperation( 6601): 	at fhk.a(PG:908)
E/HttpOperation( 6601): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6601): 	at ihi.a(PG:22)
E/HttpOperation( 6601): 	at kft.a(PG:91)
E/HttpOperation( 6601): 	at kfv.a(PG:62)
E/HttpOperation( 6601): 	... 8 more
E/HttpOperation( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6601): 	at gde.c(Unknown Source)
E/HttpOperation( 6601): 	at gde.b(Unknown Source)
E/HttpOperation( 6601): 	at ihi.a(PG:19)
E/HttpOperation( 6601): 	... 10 more
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
D/SecContentProvider2(  902): mCursor = null
,D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6601): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6601): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6601): 	at kfv.a(PG:65)
E/HttpOperation( 6601): 	at kff.u(PG:385)
E/HttpOperation( 6601): 	at kfb.a(PG:29)
E/HttpOperation( 6601): 	at kff.l(PG:132)
E/HttpOperation( 6601): 	at ieo.a(PG:43)
E/HttpOperation( 6601): 	at iep.a(PG:93)
E/HttpOperation( 6601): 	at fhn.a(PG:59)
E/HttpOperation( 6601): 	at lex.a(PG:85)
E/HttpOperation( 6601): 	at lex.b(PG:132)
E/HttpOperation( 6601): 	at fhk.a(PG:1146)
E/HttpOperation( 6601): 	at fhk.a(PG:908)
E/HttpOperation( 6601): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6601): 	at ihi.a(PG:22)
E/HttpOperation( 6601): 	at kft.a(PG:91)
E/HttpOperation( 6601): 	at kfv.a(PG:62)
E/HttpOperation( 6601): 	... 12 more
E/HttpOperation( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6601): 	at gde.c(Unknown Source)
E/HttpOperation( 6601): 	at gde.b(Unknown Source)
E/HttpOperation( 6601): 	at ihi.a(PG:19)
E/HttpOperation( 6601): 	... 14 more
E/ExperimentLoader( 6601): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6601): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6601): 	at kfv.a(PG:65)
E/ExperimentLoader( 6601): 	at kff.u(PG:385)
E/ExperimentLoader( 6601): 	at kfb.a(PG:29)
E/ExperimentLoader( 6601): 	at kff.l(PG:132)
E/ExperimentLoader( 6601): 	at ieo.a(PG:43)
E/ExperimentLoader( 6601): 	at iep.a(PG:93)
E/ExperimentLoader( 6601): 	at fhn.a(PG:59)
E/ExperimentLoader( 6601): 	at lex.a(PG:85)
E/ExperimentLoader( 6601): 	at lex.b(PG:132)
E/ExperimentLoader( 6601): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6601): 	at fhk.a(PG:908)
E/ExperimentLoader( 6601): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6601): 	at ihi.a(PG:22)
E/ExperimentLoader( 6601): 	at kft.a(PG:91)
E/ExperimentLoader( 6601): 	at kfv.a(PG:62)
E/ExperimentLoader( 6601): 	... 12 more
E/ExperimentLoader( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6601): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6601): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6601): 	at ihi.a(PG:19)
E/ExperimentLoader( 6601): 	... 14 more
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/SQLiteLog( 1675): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
D/SecContentProvider2(  902): mCursor = null
,D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6601): [getaccountstatus] Unexpected exception
E/HttpOperation( 6601): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6601): 	at kfv.a(PG:65)
E/HttpOperation( 6601): 	at kff.u(PG:385)
E/HttpOperation( 6601): 	at kfb.a(PG:29)
E/HttpOperation( 6601): 	at ixd.a(PG:248)
E/HttpOperation( 6601): 	at ixd.b(PG:206)
E/HttpOperation( 6601): 	at ixd.a(PG:175)
E/HttpOperation( 6601): 	at fig.a(PG:78)
E/HttpOperation( 6601): 	at lex.a(PG:85)
E/HttpOperation( 6601): 	at lex.b(PG:132)
E/HttpOperation( 6601): 	at fhk.a(PG:1146)
E/HttpOperation( 6601): 	at fhk.a(PG:908)
E/HttpOperation( 6601): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6601): 	at ihi.a(PG:22)
E/HttpOperation( 6601): 	at kft.a(PG:91)
E/HttpOperation( 6601): 	at kfv.a(PG:62)
E/HttpOperation( 6601): 	... 12 more
E/HttpOperation( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6601): 	at gde.c(Unknown Source)
E/HttpOperation( 6601): 	at gde.b(Unknown Source)
E/HttpOperation( 6601): 	at ihi.a(PG:19)
E/HttpOperation( 6601): 	... 14 more
,E/EsSyncAdapterService( 6601): Sync failure
E/EsSyncAdapterService( 6601): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6601): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6601): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6601): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6601): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6601): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6601): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6601): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6601): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6601): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6601): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6601): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6601): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6601): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6601): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6601): 	... 10 more
E/EsSyncAdapterService( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6601): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6601): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6601): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6601): 	... 12 more
E/EsSyncAdapterService( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6601): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6601): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6601): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6601): 	... 14 more
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  902): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 161206, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecContentProvider2(  902): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  902): mCursor = null
,D/Finsky  ( 6632): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6632): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6632): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SQLiteLog( 1675): (10) POSIX Error : 11 SQLite Error : 3850
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 75s ago
,E/Watchdog(  902): !@Sync 5
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  902): SIOP:: AP = 300, PST = 341, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  902): SIOP:: AP = 300, PST = 335, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  902): waitForAlarm result :4
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  902): stay LED for fully charged
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/VacuumService( 1675): Vacuum at: now=1452688739209 tag=VacuumService
,I/GoogleURLConnFactory( 1675): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
D/SecContentProvider2(  902): mCursor = null
,D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/Uploader( 1675): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1675): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1675): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1675): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1675): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1675): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1675): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1675): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1675): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1675): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1675): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1675): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1675): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/System.out( 1675): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1675): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1675): (HTTPLog)-Thread-200-942303389: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1675): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1675, getuid(): 10012
,I/qtaguid ( 1675): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1675, getuid(): 10012
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1675): No account for auth token provided
,I/qtaguid ( 1675): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1675, getuid(): 10012
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1675): No account for auth token provided
,I/qtaguid ( 1675): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1675, getuid(): 10012
,D/Finsky  ( 6632): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6632): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6632): [1] 5.onFinished: Giving up after 6 failures.
,V/AlarmManager(  902): waitForAlarm result :8
,W/Uploader( 1675): No account for auth token provided
,I/qtaguid ( 1675): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1675, getuid(): 10012
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Uploader( 1675): No account for auth token provided
,I/qtaguid ( 1675): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1675, getuid(): 10012
,W/Uploader( 1675):  no longer exists, so no auth token.
,I/qtaguid ( 1675): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1675, getuid(): 10012
,E/SQLiteLog( 1675): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  902): SIOP:: AP = 300, PST = 329, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  902): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7349): Starting books sync, d
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
,D/SecContentProvider2(  902): mCursor = null
D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1675): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1675): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1675): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1675): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7349): Authentication error
E/BooksAccountManager( 7349): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7349): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7349): null auth token
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/qtaguid ( 7349): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7349, getuid(): 10082
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/qtaguid ( 7349): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7349, getuid(): 10082
,I/qtaguid ( 7349): Untagging socket 34
,W/ApiaryClient( 7349): Error response from books API: {
W/ApiaryClient( 7349):  "error": {
W/ApiaryClient( 7349):   "errors": [
W/ApiaryClient( 7349):    {
W/ApiaryClient( 7349):     "domain": "global",
W/ApiaryClient( 7349):     "reason": "required",
W/ApiaryClient( 7349):     "message": "Login Required",
W/ApiaryClient( 7349):     "locationType": "header",
W/ApiaryClient( 7349):     "location": "Authorization"
W/ApiaryClient( 7349):    }
W/ApiaryClient( 7349):   ],
W/ApiaryClient( 7349):   "code": 401,
W/ApiaryClient( 7349):   "message": "Login Required"
W/ApiaryClient( 7349):  }
W/ApiaryClient( 7349): }
,W/ApiaryClient( 7349): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7349): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-524361144798263478&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7349): Headers suppressed
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
,D/SecContentProvider2(  902): mCursor = null
D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1675): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1675): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1675): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1675): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7349): Authentication error
E/BooksAccountManager( 7349): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7349): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7349): null auth token
,I/qtaguid ( 7349): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7349, getuid(): 10082
,I/qtaguid ( 7349): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7349, getuid(): 10082
,I/qtaguid ( 7349): Untagging socket 34
,W/ApiaryClient( 7349): Error response from books API: {
W/ApiaryClient( 7349):  "error": {
W/ApiaryClient( 7349):   "errors": [
W/ApiaryClient( 7349):    {
W/ApiaryClient( 7349):     "domain": "global",
W/ApiaryClient( 7349):     "reason": "required",
W/ApiaryClient( 7349):     "message": "Login Required",
W/ApiaryClient( 7349):     "locationType": "header",
W/ApiaryClient( 7349):     "location": "Authorization"
W/ApiaryClient( 7349):    }
W/ApiaryClient( 7349):   ],
W/ApiaryClient( 7349):   "code": 401,
W/ApiaryClient( 7349):   "message": "Login Required"
W/ApiaryClient( 7349):  }
W/ApiaryClient( 7349): }
,W/ApiaryClient( 7349): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7349): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-524361144798263478&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7349): Headers suppressed
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 105s ago
,I/PowerManagerService(  902): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  902): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  902): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=902, ws=WorkSource{10082}) (elapsedTime=2306)
,E/Watchdog(  902): !@Sync 6
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     ( 1675): Explicit concurrent mark sweep GC freed 50129(2MB) AllocSpace objects, 64(4MB) LOS objects, 39% free, 18MB/30MB, paused 843us total 95.484ms
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1675): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
,D/SecContentProvider2(  902): mCursor = null
D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1675): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1675): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1675): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1675): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7349): Authentication error
E/BooksAccountManager( 7349): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7349): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7349): null auth token
,I/qtaguid ( 7349): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7349, getuid(): 10082
,I/qtaguid ( 7349): Untagging socket 34
,W/ApiaryClient( 7349): Error response from books API: {
W/ApiaryClient( 7349):  "error": {
W/ApiaryClient( 7349):   "errors": [
W/ApiaryClient( 7349):    {
W/ApiaryClient( 7349):     "domain": "global",
W/ApiaryClient( 7349):     "reason": "required",
W/ApiaryClient( 7349):     "message": "Login Required",
W/ApiaryClient( 7349):     "locationType": "header",
W/ApiaryClient( 7349):     "location": "Authorization"
W/ApiaryClient( 7349):    }
W/ApiaryClient( 7349):   ],
W/ApiaryClient( 7349):   "code": 401,
W/ApiaryClient( 7349):   "message": "Login Required"
W/ApiaryClient( 7349):  }
W/ApiaryClient( 7349): }
,W/ApiaryClient( 7349): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7349): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-524361144798263478&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7349): Headers suppressed
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7349): Soft error
E/BooksSync( 7349): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7349): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-524361144798263478&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7349): Headers suppressed
E/BooksSync( 7349): 
E/BooksSync( 7349): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7349): Sync error
E/BooksSync( 7349): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7349): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-524361144798263478&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7349): Headers suppressed
E/BooksSync( 7349): 
E/BooksSync( 7349): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7349): Finished books sync
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  902): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 162795, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  902): Explicit concurrent mark sweep GC freed 49955(2MB) AllocSpace objects, 32(967KB) LOS objects, 30% free, 36MB/52MB, paused 2.040ms total 170.369ms
,D/SecContentProvider2(  902): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  902): mCursor = null
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1675): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
,D/SecContentProvider2(  902): mCursor = null
D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6601): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 6601): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6601): 	at kfv.a(PG:65)
E/HttpOperation( 6601): 	at kff.u(PG:385)
E/HttpOperation( 6601): 	at kfb.a(PG:29)
E/HttpOperation( 6601): 	at kff.l(PG:132)
E/HttpOperation( 6601): 	at dsf.a(PG:807)
E/HttpOperation( 6601): 	at fhk.a(PG:1126)
E/HttpOperation( 6601): 	at fhk.a(PG:908)
E/HttpOperation( 6601): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6601): 	at ihi.a(PG:22)
E/HttpOperation( 6601): 	at kft.a(PG:91)
E/HttpOperation( 6601): 	at kfv.a(PG:62)
E/HttpOperation( 6601): 	... 8 more
E/HttpOperation( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6601): 	at gde.c(Unknown Source)
E/HttpOperation( 6601): 	at gde.b(Unknown Source)
E/HttpOperation( 6601): 	at ihi.a(PG:19)
E/HttpOperation( 6601): 	... 10 more
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/ProcessCpuTracker(  902): Skipping unknown process pid 8354
,W/ProcessCpuTracker(  902): Skipping unknown process pid 8356
W/ProcessCpuTracker(  902): Skipping unknown process pid 8358
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  902): uri = 14 selection = getSealedState
D/SecContentProvider2(  902): mCursor = null
D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6601): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6601): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6601): 	at kfv.a(PG:65)
E/HttpOperation( 6601): 	at kff.u(PG:385)
E/HttpOperation( 6601): 	at kfb.a(PG:29)
E/HttpOperation( 6601): 	at kff.l(PG:132)
E/HttpOperation( 6601): 	at ieo.a(PG:43)
E/HttpOperation( 6601): 	at iep.a(PG:93)
E/HttpOperation( 6601): 	at fhn.a(PG:59)
E/HttpOperation( 6601): 	at lex.a(PG:85)
E/HttpOperation( 6601): 	at lex.b(PG:132)
E/HttpOperation( 6601): 	at fhk.a(PG:1146)
E/HttpOperation( 6601): 	at fhk.a(PG:908)
E/HttpOperation( 6601): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6601): 	at ihi.a(PG:22)
E/HttpOperation( 6601): 	at kft.a(PG:91)
E/HttpOperation( 6601): 	at kfv.a(PG:62)
E/HttpOperation( 6601): 	... 12 more
E/HttpOperation( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6601): 	at gde.c(Unknown Source)
E/HttpOperation( 6601): 	at gde.b(Unknown Source)
E/HttpOperation( 6601): 	at ihi.a(PG:19)
E/HttpOperation( 6601): 	... 14 more
,E/ExperimentLoader( 6601): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6601): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6601): 	at kfv.a(PG:65)
E/ExperimentLoader( 6601): 	at kff.u(PG:385)
E/ExperimentLoader( 6601): 	at kfb.a(PG:29)
E/ExperimentLoader( 6601): 	at kff.l(PG:132)
E/ExperimentLoader( 6601): 	at ieo.a(PG:43)
E/ExperimentLoader( 6601): 	at iep.a(PG:93)
E/ExperimentLoader( 6601): 	at fhn.a(PG:59)
E/ExperimentLoader( 6601): 	at lex.a(PG:85)
E/ExperimentLoader( 6601): 	at lex.b(PG:132)
E/ExperimentLoader( 6601): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6601): 	at fhk.a(PG:908)
E/ExperimentLoader( 6601): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6601): 	at ihi.a(PG:22)
E/ExperimentLoader( 6601): 	at kft.a(PG:91)
E/ExperimentLoader( 6601): 	at kfv.a(PG:62)
E/ExperimentLoader( 6601): 	... 12 more
E/ExperimentLoader( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6601): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6601): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6601): 	at ihi.a(PG:19)
E/ExperimentLoader( 6601): 	... 14 more
D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,E/SQLiteLog( 1675): (10) POSIX Error : 11 SQLite Error : 3850
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
D/SecContentProvider2(  902): mCursor = null
,D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6601): [getaccountstatus] Unexpected exception
E/HttpOperation( 6601): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6601): 	at kfv.a(PG:65)
E/HttpOperation( 6601): 	at kff.u(PG:385)
E/HttpOperation( 6601): 	at kfb.a(PG:29)
E/HttpOperation( 6601): 	at ixd.a(PG:248)
E/HttpOperation( 6601): 	at ixd.b(PG:206)
E/HttpOperation( 6601): 	at ixd.a(PG:175)
E/HttpOperation( 6601): 	at fig.a(PG:78)
E/HttpOperation( 6601): 	at lex.a(PG:85)
E/HttpOperation( 6601): 	at lex.b(PG:132)
E/HttpOperation( 6601): 	at fhk.a(PG:1146)
E/HttpOperation( 6601): 	at fhk.a(PG:908)
E/HttpOperation( 6601): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6601): 	at ihi.a(PG:22)
E/HttpOperation( 6601): 	at kft.a(PG:91)
E/HttpOperation( 6601): 	at kfv.a(PG:62)
E/HttpOperation( 6601): 	... 12 more
E/HttpOperation( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6601): 	at gde.c(Unknown Source)
E/HttpOperation( 6601): 	at gde.b(Unknown Source)
E/HttpOperation( 6601): 	at ihi.a(PG:19)
E/HttpOperation( 6601): 	... 14 more
,E/EsSyncAdapterService( 6601): Sync failure
E/EsSyncAdapterService( 6601): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6601): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6601): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6601): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6601): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6601): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6601): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6601): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6601): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6601): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6601): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6601): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6601): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6601): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6601): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6601): 	... 10 more
E/EsSyncAdapterService( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6601): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6601): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6601): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6601): 	... 12 more
E/EsSyncAdapterService( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6601): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6601): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6601): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6601): 	... 14 more
,I/PhoneStatusBar( 1171): Icon Only
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/SMD     (  287): DCD ON
D/SyncManager(  902): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 194909, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  902): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  902): mCursor = null
,E/SQLiteLog( 1675): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  902): SIOP:: AP = 300, PST = 324, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  902): SIOP:: AP = 300, PST = 313, CUR = 300
,E/SMD     (  287): DCD ON
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  902): SIOP:: AP = 290, PST = 306, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  902): waitForAlarm result :4
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  902): stay LED for fully charged
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,E/Watchdog(  902): !@Sync 7
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 1
,I/PowerManagerService(  902): [PWL] Off : 140s ago
,D/SSRM:m  (  902): SIOP:: AP = 290, PST = 302, CUR = 300
,E/SMD     (  287): DCD ON
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  902): SIOP:: AP = 290, PST = 299, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  902): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:m  (  902): SIOP:: AP = 290, PST = 297, CUR = 300
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,V/AlarmManager(  902): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  902): stay LED for fully charged
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7349): Starting books sync, d
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
D/SecContentProvider2(  902): mCursor = null
,D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1675): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1675): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1675): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1675): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7349): Authentication error
E/BooksAccountManager( 7349): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7349): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7349): null auth token
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
I/qtaguid ( 7349): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7349, getuid(): 10082
,D/PanelView( 1171): There is/are notification(s) 
,I/qtaguid ( 7349): Untagging socket 34
,W/ApiaryClient( 7349): Error response from books API: {
W/ApiaryClient( 7349):  "error": {
W/ApiaryClient( 7349):   "errors": [
W/ApiaryClient( 7349):    {
W/ApiaryClient( 7349):     "domain": "global",
W/ApiaryClient( 7349):     "reason": "required",
W/ApiaryClient( 7349):     "message": "Login Required",
W/ApiaryClient( 7349):     "locationType": "header",
W/ApiaryClient( 7349):     "location": "Authorization"
W/ApiaryClient( 7349):    }
W/ApiaryClient( 7349):   ],
W/ApiaryClient( 7349):   "code": 401,
W/ApiaryClient( 7349):   "message": "Login Required"
W/ApiaryClient( 7349):  }
W/ApiaryClient( 7349): }
,W/ApiaryClient( 7349): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7349): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4732753523266675330&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7349): Headers suppressed
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
,D/SecContentProvider2(  902): mCursor = null
,D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1675): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1675): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1675): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1675): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7349): Authentication error
E/BooksAccountManager( 7349): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7349): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7349): null auth token
,I/qtaguid ( 7349): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7349, getuid(): 10082
,I/qtaguid ( 7349): Untagging socket 34
,W/ApiaryClient( 7349): Error response from books API: {
W/ApiaryClient( 7349):  "error": {
W/ApiaryClient( 7349):   "errors": [
W/ApiaryClient( 7349):    {
W/ApiaryClient( 7349):     "domain": "global",
W/ApiaryClient( 7349):     "reason": "required",
W/ApiaryClient( 7349):     "message": "Login Required",
W/ApiaryClient( 7349):     "locationType": "header",
W/ApiaryClient( 7349):     "location": "Authorization"
W/ApiaryClient( 7349):    }
W/ApiaryClient( 7349):   ],
W/ApiaryClient( 7349):   "code": 401,
W/ApiaryClient( 7349):   "message": "Login Required"
W/ApiaryClient( 7349):  }
W/ApiaryClient( 7349): }
,W/ApiaryClient( 7349): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7349): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4732753523266675330&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7349): Headers suppressed
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,E/Watchdog(  902): !@Sync 8
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
,D/SecContentProvider2(  902): mCursor = null
,D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1675): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1675): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1675): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1675): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1675): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7349): Authentication error
E/BooksAccountManager( 7349): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7349): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7349): null auth token
,I/qtaguid ( 7349): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7349, getuid(): 10082
,I/qtaguid ( 7349): Untagging socket 34
,W/ApiaryClient( 7349): Error response from books API: {
W/ApiaryClient( 7349):  "error": {
W/ApiaryClient( 7349):   "errors": [
W/ApiaryClient( 7349):    {
W/ApiaryClient( 7349):     "domain": "global",
W/ApiaryClient( 7349):     "reason": "required",
W/ApiaryClient( 7349):     "message": "Login Required",
W/ApiaryClient( 7349):     "locationType": "header",
W/ApiaryClient( 7349):     "location": "Authorization"
W/ApiaryClient( 7349):    }
W/ApiaryClient( 7349):   ],
W/ApiaryClient( 7349):   "code": 401,
W/ApiaryClient( 7349):   "message": "Login Required"
W/ApiaryClient( 7349):  }
W/ApiaryClient( 7349): }
,W/ApiaryClient( 7349): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7349): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4732753523266675330&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7349): Headers suppressed
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7349): Soft error
E/BooksSync( 7349): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7349): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4732753523266675330&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7349): Headers suppressed
E/BooksSync( 7349): 
E/BooksSync( 7349): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7349): Sync error
E/BooksSync( 7349): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7349): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4732753523266675330&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7349): Headers suppressed
E/BooksSync( 7349): 
E/BooksSync( 7349): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7349): Finished books sync
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  902): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 228243, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  902): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  902): mCursor = null
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  902): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  287): DCD ON
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 180s ago
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:m  (  902): SIOP:: AP = 290, PST = 294, CUR = 300
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
,I/MotionRecognitionService(  902): setPowerConnected  = true
,D/BatteryService(  902): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  902): SIOP:: AP = 290, PST = 293, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  902): waitForAlarm result :4
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  902): stay LED for fully charged
D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
D/SecContentProvider2(  902): mCursor = null
,D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6601): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6601): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6601): 	at kfv.a(PG:65)
E/HttpOperation( 6601): 	at kff.u(PG:385)
E/HttpOperation( 6601): 	at kfb.a(PG:29)
E/HttpOperation( 6601): 	at kff.l(PG:132)
E/HttpOperation( 6601): 	at dsf.a(PG:807)
E/HttpOperation( 6601): 	at fhk.a(PG:1126)
E/HttpOperation( 6601): 	at fhk.a(PG:908)
E/HttpOperation( 6601): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6601): 	at ihi.a(PG:22)
E/HttpOperation( 6601): 	at kft.a(PG:91)
E/HttpOperation( 6601): 	at kfv.a(PG:62)
E/HttpOperation( 6601): 	... 8 more
E/HttpOperation( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6601): 	at gde.c(Unknown Source)
E/HttpOperation( 6601): 	at gde.b(Unknown Source)
E/HttpOperation( 6601): 	at ihi.a(PG:19)
E/HttpOperation( 6601): 	... 10 more
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
D/SecContentProvider2(  902): mCursor = null
,D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6601): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6601): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6601): 	at kfv.a(PG:65)
E/HttpOperation( 6601): 	at kff.u(PG:385)
E/HttpOperation( 6601): 	at kfb.a(PG:29)
E/HttpOperation( 6601): 	at kff.l(PG:132)
E/HttpOperation( 6601): 	at ieo.a(PG:43)
E/HttpOperation( 6601): 	at iep.a(PG:93)
E/HttpOperation( 6601): 	at fhn.a(PG:59)
E/HttpOperation( 6601): 	at lex.a(PG:85)
E/HttpOperation( 6601): 	at lex.b(PG:132)
E/HttpOperation( 6601): 	at fhk.a(PG:1146)
E/HttpOperation( 6601): 	at fhk.a(PG:908)
E/HttpOperation( 6601): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6601): 	at ihi.a(PG:22)
E/HttpOperation( 6601): 	at kft.a(PG:91)
E/HttpOperation( 6601): 	at kfv.a(PG:62)
E/HttpOperation( 6601): 	... 12 more
E/HttpOperation( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6601): 	at gde.c(Unknown Source)
E/HttpOperation( 6601): 	at gde.b(Unknown Source)
E/HttpOperation( 6601): 	at ihi.a(PG:19)
E/HttpOperation( 6601): 	... 14 more
,E/ExperimentLoader( 6601): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6601): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6601): 	at kfv.a(PG:65)
E/ExperimentLoader( 6601): 	at kff.u(PG:385)
E/ExperimentLoader( 6601): 	at kfb.a(PG:29)
E/ExperimentLoader( 6601): 	at kff.l(PG:132)
E/ExperimentLoader( 6601): 	at ieo.a(PG:43)
E/ExperimentLoader( 6601): 	at iep.a(PG:93)
E/ExperimentLoader( 6601): 	at fhn.a(PG:59)
E/ExperimentLoader( 6601): 	at lex.a(PG:85)
E/ExperimentLoader( 6601): 	at lex.b(PG:132)
E/ExperimentLoader( 6601): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6601): 	at fhk.a(PG:908)
E/ExperimentLoader( 6601): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6601): 	at ihi.a(PG:22)
E/ExperimentLoader( 6601): 	at kft.a(PG:91)
E/ExperimentLoader( 6601): 	at kfv.a(PG:62)
E/ExperimentLoader( 6601): 	... 12 more
E/ExperimentLoader( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6601): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6601): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6601): 	at ihi.a(PG:19)
E/ExperimentLoader( 6601): 	... 14 more
,I/GLSUser ( 1675): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1675): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1675): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1675): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1675): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 1675): (10) POSIX Error : 11 SQLite Error : 3850
,V/BitmapFactory( 1675): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  902): uri = 14 selection = getSealedState
,D/SecContentProvider2(  902): mCursor = null
,D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,E/HttpOperation( 6601): [getaccountstatus] Unexpected exception
E/HttpOperation( 6601): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6601): 	at kfv.a(PG:65)
E/HttpOperation( 6601): 	at kff.u(PG:385)
E/HttpOperation( 6601): 	at kfb.a(PG:29)
E/HttpOperation( 6601): 	at ixd.a(PG:248)
E/HttpOperation( 6601): 	at ixd.b(PG:206)
E/HttpOperation( 6601): 	at ixd.a(PG:175)
E/HttpOperation( 6601): 	at fig.a(PG:78)
E/HttpOperation( 6601): 	at lex.a(PG:85)
E/HttpOperation( 6601): 	at lex.b(PG:132)
E/HttpOperation( 6601): 	at fhk.a(PG:1146)
E/HttpOperation( 6601): 	at fhk.a(PG:908)
E/HttpOperation( 6601): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6601): 	at ihi.a(PG:22)
E/HttpOperation( 6601): 	at kft.a(PG:91)
E/HttpOperation( 6601): 	at kfv.a(PG:62)
E/HttpOperation( 6601): 	... 12 more
E/HttpOperation( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6601): 	at gde.c(Unknown Source)
E/HttpOperation( 6601): 	at gde.b(Unknown Source)
E/HttpOperation( 6601): 	at ihi.a(PG:19)
E/HttpOperation( 6601): 	... 14 more
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/EsSyncAdapterService( 6601): Sync failure
E/EsSyncAdapterService( 6601): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6601): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6601): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6601): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6601): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6601): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6601): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6601): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6601): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6601): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6601): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6601): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6601): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6601): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6601): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6601): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6601): 	... 10 more
E/EsSyncAdapterService( 6601): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6601): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6601): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6601): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6601): 	... 12 more
E/EsSyncAdapterService( 6601): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6601): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6601): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6601): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6601): 	... 14 more
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  902): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 261876, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2857): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  902): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  902): mCursor = null
,E/SQLiteLog( 1675): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD ON
,E/Watchdog(  902): !@Sync 9
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  902): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  902): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  902): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  902): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,D/TimaService(  902): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  902): TimaServiceHandler.handleMessage what =1
,D/TimaService(  902): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  902): initializing...
,I/TLC_TIMA_PKM_initialize(  902): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize(  902): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  902): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  902): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  902): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  902): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  902): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  902): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  902): App is not loaded in QSEE
,D/QSEECOMAPI: (  902): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  902): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  902): Trustlet response is completed
,V/AlarmManager(  902): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  902): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  902): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  902): stay LED for fully charged
,D/BatteryService(  902): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  902):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  902): Plugged
I/MotionRecognitionService(  902): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  902): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  902): [PWL] Off : 225s ago
,I/PowerManagerService(  902): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  902): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  902): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=902, ws=null) (elapsedTime=2411)
,E/Watchdog(  902): !@Sync 10
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel(  902): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  902): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  902): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  902): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD ON,
,D/SSRM:m  (  902): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/jxcore-log( 7428): --= Surplus to requirements =--
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ****TEST TOOK:  ms ****
I/jxcore-log( 7428): 
I/jxcore-log( 7428): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7428): 
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/AndroidRuntime( 8479): 
D/AndroidRuntime( 8479): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8479): CheckJNI is OFF
D/AndroidRuntime( 8479): setted country_code = Germany
D/AndroidRuntime( 8479): setted countryiso_code = DE
,D/AndroidRuntime( 8479): setted sales_code = DBT
,D/AndroidRuntime( 8479): readGMSProperty: start
,D/AndroidRuntime( 8479): readGMSProperty: already setted!!
,D/AndroidRuntime( 8479): readGMSProperty: end
,D/AndroidRuntime( 8479): addProductProperty: start
,E/AffinityControl( 8479): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8479): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  902): START PACKAGE DELETE: observer{871962646}
D/PackageManager(  902): pkg{<packageName>}
D/PackageManager(  902): user{0}
D/PackageManager(  902): caller{2000}
D/PackageManager(  902): flags{3}
D/PersonaManagerService(  902): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  902): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  902): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  902): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  902): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  902): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  902): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  902): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  902): getApplicationUninstallationEnabled
D/ApplicationPolicy(  902): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  902): !@killApplicatoin: 10200, uninstall pkg
,I/ActivityManager(  902): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
,I/ActivityManager(  902): Killing 7428:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
,I/ActivityManager(  902):   Force finishing activity ActivityRecord{2d9dc3de u0 com.test.thalitest/.MainActivity t18}
,W/ActivityManager(  902): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/DBG_DM  ( 3781): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
,I/DBG_DM  ( 3781): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 56
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/DBG_DM  ( 3781): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/WifiService(  902): Client connection lost with reason: 4
,I/WindowState(  902): WIN DEATH: Window{793fb4a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  251): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
I/SurfaceFlinger(  251): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SurfaceFlinger(  251): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,I/DBG_DM  ( 3781): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3781): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 56
,I/DBG_DM  ( 3781): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/DBG_DM  ( 3781): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3781): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/ActivityManager(  902): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  902):   Force finishing activity ActivityRecord{2d9dc3de u0 com.test.thalitest/.MainActivity t18 f}
D/SecContentProvider2(  902): uri = 14 selection = getSealedState
W/ActivityManager(  902): Duplicate finish request for ActivityRecord{2d9dc3de u0 com.test.thalitest/.MainActivity t18 f}
D/SecContentProvider2(  902): mCursor = null
D/SecContentProvider2(  902): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  902): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 3781): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 56
,I/DBG_DM  ( 3781): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 3781): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3781): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false,
I/DBG_DM  ( 3781): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 3781): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager(  902): post active user change for 0
D/KnoxTimeoutHandler(  902): postActiveUserChange for user 0
,I/DBG_DM  ( 3781): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
,D/FocusedStackFrame(  902): Set to : 0
I/art     ( 4551): Explicit concurrent mark sweep GC freed 5010(278KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 328us total 23.804ms
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,E/SamsungIME( 1866): mOCRHelper is null
I/InputReader(  902): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1578): Explicit concurrent mark sweep GC freed 60077(3MB) AllocSpace objects, 0(0B) LOS objects, 39% free, 16MB/27MB, paused 464us total 70.130ms
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,W/GeofencerStateMachine( 2180): Ignoring removeGeofence because network location is disabled.
,D/KnoxTimeoutHandler(  902): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  902): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/SurfaceFlinger(  251): id=17 createSurf (1080x1920),2 flag=404, com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/StatusBarManagerService(  902): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
I/KLMS-2.4.503: ( 7680): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager( 2857): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/KLMS-2.4.503: ( 7680): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1452688880120
,D/SurfaceWidgetView( 1474): destroyHardwareResources():164062011
I/KLMS-2.4.503: ( 7680): MainReciver(): PACKAGE_REMOVED
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/KLMS-2.4.503: ( 7680): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,V/WindowOrientationListener(  902): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,V/WindowOrientationListener(  902): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  902): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  902): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  902): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/Launcher( 1474): onRestart, Launcher: 289142081
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/Launcher( 1474): onStart, Launcher: 289142081
D/Launcher.HomeView( 1474): onStart
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2251): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/Launcher.HomeView( 1474): onStop
,D/SurfaceWidget.Renderer( 2251): [237392/6] SurfaceWidget drawing first frame
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/SurfaceFlinger(  251): id=17 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/8)
,I/SurfaceFlinger(  251): id=17 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/SurfaceFlinger(  251): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  902): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager( 2857): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/StatusBarManagerService(  902): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/Timeline( 3781): Timeline: Activity_idle id: android.os.BinderProxy@3a73cc52 time:323965
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/SecContentProvider2(  902): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  902): mCursor = null
,D/RegisteredServicesCache( 1447): empty dynamic service
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/InputMethodManagerService(  902): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/talkback/talkback.apk
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService(  902): Got RemoteException sending setActive(false) notification to pid 7428 uid 10200
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/ActivityManager(  902): mDVFSHelper.release()
I/Timeline(  902): Timeline: Activity_windows_visible id: ActivityRecord{2ad3e613 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:324082
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8513): MountEmulatedStorage()
I/libpersona( 8513): KNOX_SDCARD checking this for 10104
E/Zygote  ( 8513): v2
I/libpersona( 8513): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8513 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
I/SELinux ( 8513): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8513): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8513): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  902): PackageReceiver onReceive()
,I/HarmonyEASService(  902): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  902): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  902): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  902): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  902): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  902): uID is 10200
V/EnterpriseBillingPolicy(  902): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  902): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  902): getProfileForApplication - exit null
,V/EnterpriseBillingPolicy(  902): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  902): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  902): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  902): getBillingProfileForVpnEngine - end - null
D/TimaKeyStoreProvider( 8513): TimaSignature is unavailable
,D/EnterpriseDeviceManagerService(  902): Package has changed for user 0
D/EnterpriseDeviceManagerService(  902): Admin package name: com.google.android.gms
,D/ActivityThread( 8513): Added TimaKeyStore provider
,D/TaskPersister(  902): removeObsoleteFile: deleting file=18_task.xml
,D/TaskPersister(  902): removeObsoleteFile: deleting file=17_task.xml
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,D/ResourcesManager( 8513): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     (  902): Explicit concurrent mark sweep GC freed 69864(4MB) AllocSpace objects, 56(1481KB) LOS objects, 30% free, 37MB/53MB, paused 5.212ms total 385.123ms
I/art     (  902): WaitForGcToComplete blocked for 199.772ms for cause Explicit
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Books/Books.apk
,D/elm:14451( 8513): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8513): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8513): MDMBridge.setEnterpriseBridge()
,D/elm:14451( 8513): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/elm:14451( 8513): ElmAgentService : onCreate()
,D/elm:14451( 8513): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14451( 8513): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8513): MDMBridge.getInstance()
,D/elm:14451( 8513): MDMBridge.getAllLicenseInfoFromSDK()
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 7990): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver( 7990): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7990): onReceive() : package name is not s health. Return !!!
,D/PackageManager(  902): delete codoeFile: 
,D/elm:14451( 8513): MDMBridge.getAllLicenseInfoFromSDK()
,D/PackageManager(  902): result of delete: 1{871962646}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/PCWCLIENTTRACE_PushUtil( 6754): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6754): sales region : global
D/ConnectivityService(  902): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PCWCLIENTTRACE_PushUtil( 6754): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6754): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/AndroidRuntime( 8479): Shutting down VM
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/elm:14451( 8513): ElmAgentService : onDestroy().
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,E/Zygote  ( 8533): MountEmulatedStorage()
I/libpersona( 8533): KNOX_SDCARD checking this for 10038
E/Zygote  ( 8533): v2
I/libpersona( 8533): KNOX_SDCARD not a persona
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     (  902): Explicit concurrent mark sweep GC freed 10600(653KB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 36MB/52MB, paused 1.854ms total 110.037ms
I/art     (  902): WaitForGcToComplete blocked for 127.391ms for cause Explicit
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/ActivityManager(  902): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8533 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/ActivityManager(  902): Killing 7039:com.samsung.helphub/1000 (adj 15): bgCount ##41
,I/SELinux ( 8533): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8533): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8533): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/TimaKeyStoreProvider( 8533): TimaSignature is unavailable
,D/ActivityThread( 8533): Added TimaKeyStore provider
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 8533): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  902): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  902): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  902): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,W/libprocessgroup(  902): failed to open /acct/uid_1000/pid_7039/cgroup.procs: No such file or directory
,D/ResourcesManager(  902): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     (  902): Explicit concurrent mark sweep GC freed 3223(189KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 1.484ms total 97.668ms
,E/SPPClientService( 8533): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8533): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 8533): PushLog.txt file is not deleted.
D/SPPClientService( 8533): PushLog.txt file is not deleted.
D/SPPClientService( 8533): ============PushLog. stop!
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,E/Zygote  ( 8549): MountEmulatedStorage()
E/Zygote  ( 8549): v2
I/libpersona( 8549): KNOX_SDCARD checking this for 10042
I/libpersona( 8549): KNOX_SDCARD not a persona
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/ActivityManager(  902): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8549 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  902): Killing 7075:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  902): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  902): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  902): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  902): onPackageRemoved : com.test.thalitest
,I/SELinux ( 8549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/SELinux ( 8549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8549): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 7951): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7951): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7951): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup(  902): failed to open /acct/uid_10166/pid_7075/cgroup.procs: No such file or directory
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/TimaKeyStoreProvider( 8549): TimaSignature is unavailable
,D/ActivityThread( 8549): Added TimaKeyStore provider
,W/ResourcesManager( 7951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/ResourcesManager( 8549): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
W/ResourcesManager( 7951): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8549): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8549): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/ResourcesManager( 7951): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/ResourcesManager( 7951): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7951): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7951): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7951): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SQLiteDatabase( 8549): Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
E/SQLiteDatabase( 8549): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8549): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8549): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 8549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 8549): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8549): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 8549): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 8549): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8549): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 8549): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8549): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8549): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8549): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:462)
E/SQLiteDatabase( 8549): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 8549): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 8549): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/SQLiteDatabase( 8549): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/SQLiteDatabase( 8549): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/SQLiteDatabase( 8549): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8549): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/SQLiteDatabase( 8549): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8549): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 8549): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/SQLiteDatabase( 8549): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8549): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8549): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 8549): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 8549): Shutting down VM
,E/AndroidRuntime( 8549): FATAL EXCEPTION: main
E/AndroidRuntime( 8549): Process: com.samsung.android.sdk.samsunglink, PID: 8549
E/AndroidRuntime( 8549): java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8549): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5456)
E/AndroidRuntime( 8549): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/AndroidRuntime( 8549): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/AndroidRuntime( 8549): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8549): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8549): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8549): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8549): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8549): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8549): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8549): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8549): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8549): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8549): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 8549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 8549): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8549): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/AndroidRuntime( 8549): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/AndroidRuntime( 8549): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8549): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/AndroidRuntime( 8549): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 8549): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8549): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8549): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:462)
E/AndroidRuntime( 8549): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 8549): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 8549): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/AndroidRuntime( 8549): 	... 11 more
V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.samsung.android.sdk.samsunglink
I/SA      ( 6792): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
I/SA      ( 6792): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10200 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/Process ( 8549): Sending signal. PID: 8549 SIG: 9
E/lowmemorykiller(  248): Error writing /proc/8549/oom_score_adj; errno=22
I/ActivityManager(  902): Killing 6673:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
E/DropBoxManagerService(  902): Can't write: system_app_crash
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop186.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:14540)
E/DropBoxManagerService(  902): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  902): 	... 5 more
I/ActivityManager(  902): Process com.samsung.android.sdk.samsunglink (pid 8549)(adj 11) has died(144,547)
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/SharedPreferencesImpl( 6024): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/Zygote  ( 8572): MountEmulatedStorage()
E/Zygote  ( 8572): v2
I/libpersona( 8572): KNOX_SDCARD checking this for 10050
I/libpersona( 8572): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=8572 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux ( 8572): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
E/SELinux ( 8572): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/EventHub(  902): Removing device '/dev/input/event4' due to inotify event
W/libprocessgroup(  902): failed to open /acct/uid_10012/pid_6673/cgroup.procs: No such file or directory
,I/EventHub(  902): Removing device '/dev/input/event5' due to inotify event
,D/TimaKeyStoreProvider( 8572): TimaSignature is unavailable
,D/ActivityThread( 8572): Added TimaKeyStore provider
,D/ResourcesManager( 8572): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8572): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8572): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8572): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8572): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8572): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ContextImpl( 8572): Unable to create files subdir /data/data/com.android.mms/cache
E/ActivityThread( 8572): Unable to setupGraphicsSupport due to missing cache directory
,D/AndroidRuntime( 8572): Shutting down VM
,E/AndroidRuntime( 8572): FATAL EXCEPTION: main
E/AndroidRuntime( 8572): Process: com.android.mms, PID: 8572
E/AndroidRuntime( 8572): java.lang.RuntimeException: Unable to instantiate application com.android.mms.MmsApp: java.lang.ClassNotFoundException: Didn't find class "com.android.mms.MmsApp" on path: DexPathList[[zip file "/system/framework/imsmanager.jar", zip file "/system/framework/twframework.jar", zip file "/system/framework/multiwindow.jar", zip file "/system/framework/com.google.android.maps.jar", zip file "/system/framework/minimode.jar", zip file "/system/priv-app/SecMms_Candy/SecMms_Candy.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8572): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:625)
E/AndroidRuntime( 8572): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4980)
E/AndroidRuntime( 8572): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8572): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8572): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8572): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8572): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8572): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8572): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8572): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8572): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8572): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.android.mms.MmsApp" on path: DexPathList[[zip file "/system/framework/imsmanager.jar", zip file "/system/framework/twframework.jar", zip file "/system/framework/multiwindow.jar", zip file "/system/framework/com.google.android.maps.jar", zip file "/system/framework/minimode.jar", zip file "/system/priv-app/SecMms_Candy/SecMms_Candy.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8572): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 8572): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 8572): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 8572): 	at android.app.Instrumentation.newApplication(Instrumentation.java:988)
E/AndroidRuntime( 8572): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:620)
E/AndroidRuntime( 8572): 	... 10 more
E/AndroidRuntime( 8572): 	Suppressed: java.io.IOException: Zip archive '/system/priv-app/SecMms_Candy/SecMms_Candy.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 8572): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 8572): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 8572): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 8572): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 8572): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 8572): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 8572): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 8572): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 8572): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 8572): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
E/AndroidRuntime( 8572): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8572): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8572): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
E/AndroidRuntime( 8572): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
E/AndroidRuntime( 8572): 		at, android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
E/AndroidRuntime( 8572): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 8572): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 8572): 		... 10 more
E/AndroidRuntime( 8572): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/SecMms_Candy/SecMms_Candy.apk'
E/AndroidRuntime( 8572): 		... 27 more
E/AndroidRuntime( 8572): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/SecMms_Candy/arm/SecMms_Candy.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 8572): 		... 27 more
E/AndroidRuntime( 8572): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 8572): 		... 27 more
E/AndroidRuntime( 8572): 	Suppressed: java.lang.ClassNotFoundException: com.android.mms.MmsApp
E/AndroidRuntime( 8572): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 8572): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 8572): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 8572): 		at java.lang.ClassLoade
,V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.android.mms
,I/Process ( 8572): Sending signal. PID: 8572 SIG: 9
,E/DropBoxManagerService(  902): Can't write: system_app_crash
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop187.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:14540)
E/DropBoxManagerService(  902): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  902): 	... 5 more
I/TactileAssist(  902): enable value -1
I/TactileAssist(  902): internal enable value -1
I/TactileAssist(  902): intensity value -1
I/TactileAssist(  902): saveAppList value true
,I/TactileAssist(  902): List of disabled apps :
I/TactileAssist(  902): de.zalando.mobile
,E/SharedPreferencesImpl(  902): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8588): MountEmulatedStorage()
,E/Zygote  ( 8588): v2
I/libpersona( 8588): KNOX_SDCARD checking this for 10058
I/libpersona( 8588): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=8588 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  902): Process com.android.mms (pid 8572)(adj 9) has died(146,548)
,I/art     (  317): Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 274us total 12.693ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 253us total 7.657ms
,I/EventHub(  902): Removing device '/dev/input/event6' due to inotify event
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 7.935ms
,I/SELinux ( 8588): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 8588): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8588): TimaSignature is unavailable
,D/ActivityThread( 8588): Added TimaKeyStore provider
,I/EventHub(  902): Removing device '/dev/input/event7' due to inotify event
,D/ResourcesManager( 8588): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager( 8588): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ContextImpl( 8588): Unable to create files subdir /data/data/com.sec.android.app.soundalive/cache
E/ActivityThread( 8588): Unable to setupGraphicsSupport due to missing cache directory
,D/AndroidRuntime( 8588): Shutting down VM
,E/AndroidRuntime( 8588): FATAL EXCEPTION: main
E/AndroidRuntime( 8588): Process: com.sec.android.app.soundalive, PID: 8588
E/AndroidRuntime( 8588): java.lang.RuntimeException: Unable to instantiate receiver com.sec.android.app.soundalive.compatibility.Compatibility$Receiver: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.app.soundalive.compatibility.Compatibility$Receiver" on path: DexPathList[[zip file "/system/framework/multiwindow.jar", zip file "/system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8588): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2926)
E/AndroidRuntime( 8588): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 8588): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1499)
E/AndroidRuntime( 8588): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8588): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8588): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8588): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8588): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8588): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8588): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8588): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.app.soundalive.compatibility.Compatibility$Receiver" on path: DexPathList[[zip file "/system/framework/multiwindow.jar", zip file "/system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8588): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 8588): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 8588): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 8588): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2921)
E/AndroidRuntime( 8588): 	... 9 more
E/AndroidRuntime( 8588): 	Suppressed: java.io.IOException: Zip archive '/system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 8588): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 8588): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 8588): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 8588): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 8588): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 8588): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 8588): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 8588): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 8588): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 8588): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
E/AndroidRuntime( 8588): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8588): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8588): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
E/AndroidRuntime( 8588): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
E/AndroidRuntime( 8588): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
E/AndroidRuntime( 8588): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 8588): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 8588): 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4980)
E/AndroidRuntime( 8588): 		at android.app.Act,ivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8588): 		at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8588): 		... 7 more
E/AndroidRuntime( 8588): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk'
E/AndroidRuntime( 8588): 		... 27 more
E/AndroidRuntime( 8588): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/SoundAlive_20_L/arm/SoundAlive_20_L.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 8588): 		... 27 more
E/AndroidRuntime( 8588): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 8588): 		... 27 more
E/AndroidRuntime( 8588): 	Suppressed: java.lang.ClassNotFoundException: com.sec.android.app.soundalive.compatibility.Compatibility$Receiver
E/AndroidRuntime( 8588): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 8588): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 8588): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 8588): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 8588): 		... 11 more
E/AndroidRuntime( 8588): 	Caused by: java.lang.NoC
,V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.soundalive
,I/Process ( 8588): Sending signal. PID: 8588 SIG: 9
,I/UpdateIcingCorporaServi( 1578): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/DropBoxManagerService(  902): Can't write: system_app_crash
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop188.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:14540)
E/DropBoxManagerService(  902): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  902): 	... 5 more
,E/Zygote  ( 8605): MountEmulatedStorage()
,E/Zygote  ( 8605): v2
I/libpersona( 8605): KNOX_SDCARD checking this for 10003
I/libpersona( 8605): KNOX_SDCARD not a persona
,I/EventHub(  902): Removing device '/dev/input/event8' due to inotify event
,I/ActivityManager(  902): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=8605 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/SELinux ( 8605): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
E/SELinux ( 8605): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub(  902): Removing device '/dev/input/event9' due to inotify event
,I/ActivityManager(  902): Process com.sec.android.app.soundalive (pid 8588)(adj 9) has died(144,548)
,D/TimaKeyStoreProvider( 8605): TimaSignature is unavailable
,D/ActivityThread( 8605): Added TimaKeyStore provider
,E/SQLiteLog( 1578): (10) POSIX Error : 9 SQLite Error : 3850
,E/SQLiteLog( 1578): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,F/libc    ( 1578): Fatal signal 7 (SIGBUS), code 2, fault addr 0x78d582f1 in tid 8604 (IntentService[U)
,E/audit_log( 2098): File locking failed. error= Bad file number
E/audit_log( 2098): File locking failed. error= Bad file number
,D/ResourcesManager( 8605): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,W/ContextImpl( 8605): Unable to create files subdir /data/data/com.samsung.android.intelligenceservice/cache
E/ActivityThread( 8605): Unable to setupGraphicsSupport due to missing cache directory
,I/EventHub(  902): Removing device '/dev/input/event10' due to inotify event
,D/AndroidRuntime( 8605): Shutting down VM
,E/AndroidRuntime( 8605): FATAL EXCEPTION: main
E/AndroidRuntime( 8605): Process: com.samsung.android.intelligenceservice, PID: 8605
E/AndroidRuntime( 8605): java.lang.RuntimeException: Unable to instantiate application com.samsung.android.intelligenceservice.IntelligenceServiceApplication: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.intelligenceservice.IntelligenceServiceApplication" on path: DexPathList[[zip file "/system/priv-app/intelligenceservice/intelligenceservice.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8605): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:625)
E/AndroidRuntime( 8605): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4980)
E/AndroidRuntime( 8605): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8605): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8605): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8605): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8605): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8605): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8605): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8605): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8605): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8605): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.intelligenceservice.IntelligenceServiceApplication" on path: DexPathList[[zip file "/system/priv-app/intelligenceservice/intelligenceservice.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8605): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 8605): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 8605): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 8605): 	at android.app.Instrumentation.newApplication(Instrumentation.java:988)
E/AndroidRuntime( 8605): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:620)
E/AndroidRuntime( 8605): 	... 10 more
E/AndroidRuntime( 8605): 	Suppressed: java.io.IOException: Zip archive '/system/priv-app/intelligenceservice/intelligenceservice.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 8605): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 8605): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 8605): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 8605): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 8605): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 8605): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 8605): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 8605): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 8605): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 8605): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
E/AndroidRuntime( 8605): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8605): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8605): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
E/AndroidRuntime( 8605): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
E/AndroidRuntime( 8605): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
E/AndroidRuntime( 8605): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 8605): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRunt,ime( 8605): 		... 10 more
E/AndroidRuntime( 8605): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/intelligenceservice/intelligenceservice.apk'
E/AndroidRuntime( 8605): 		... 27 more
E/AndroidRuntime( 8605): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/intelligenceservice/arm/intelligenceservice.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 8605): 		... 27 more
E/AndroidRuntime( 8605): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 8605): 		... 27 more
E/AndroidRuntime( 8605): 	Suppressed: java.lang.ClassNotFoundException: com.samsung.android.intelligenceservice.IntelligenceServiceApplication
E/AndroidRuntime( 8605): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 8605): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 8605): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 8605): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 8605): 		... 13 more
E/AndroidRuntime( 8605): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
,V/ApplicationPolicy(  902): isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  902): checkUser: useridlist=null, currentuser=0
E/DropBoxManagerService(  902): Can't write: system_app_crash
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop189.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:14540)
E/DropBoxManagerService(  902): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  902): 	... 5 more
,E/Zygote  ( 8621): MountEmulatedStorage()
I/libpersona( 8621): KNOX_SDCARD checking this for 1000
E/Zygote  ( 8621): v2
I/libpersona( 8621): KNOX_SDCARD not a persona
,I/ActivityManager(  902): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=8621 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/Process ( 8605): Sending signal. PID: 8605 SIG: 9
,I/EventHub(  902): Removing device '/dev/input/event11' due to inotify event
,I/SELinux ( 8621): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
I/Zygote  (  317): Process 1578 exited due to signal (7)
,E/SELinux ( 8621): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  902): Process com.google.android.googlequicksearchbox:search (pid 1578)(adj 1) has died(161,548)
,F/libc    (  902): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa0d5d810 in tid 1689 (Binder_D)
,F/libc    (  902): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2098): File locking failed. error= Bad file number
,D/WifiService(  902): Client connection lost with reason: 4
,I/ServiceManager(  249): service 'sec_analytics' died
I/ServiceManager(  249): service 'application_policy' died
I/ServiceManager(  249): service 'wifi_policy' died
I/ServiceManager(  249): service 'phone_restriction_policy' died
I/ServiceManager(  249): service 'remoteinjection' died
I/ServiceManager(  249): service 'mum_container_policy' died
I/ServiceManager(  249): service 'enterprise_billing_policy' died
I/ServiceManager(  249): service 'knox_timakeystore_policy' died
I/ServiceManager(  249): service 'enterprise_policy' died
I/ServiceManager(  249): service 'statusbar' died
I/ServiceManager(  249): service 'clipboard' died
I/ServiceManager(  249): service 'clipboardEx' died
I/ServiceManager(  249): service 'network_management' died
I/ServiceManager(  249): service 'ABTPersistenceService' died
I/ServiceManager(  249): service 'textservices' died
I/ServiceManager(  249): service 'network_score' died
I/ServiceManager(  249): service 'netstats' died
I/ServiceManager(  249): service 'netpolicy' died
I/ServiceManager(  249): service 'wifi' died
I/ServiceManager(  249): service 'msapwifi' died
I/ServiceManager(  249): service 'wifiscanner' died
I/ServiceManager(  249): service 'rttmanager' died
I/ServiceManager(  249): service 'wifip2p' died
I/ServiceManager(  249): service 'backup' died
I/ServiceManager(  249): service 'appwidget' died
I/ServiceManager(  249): service 'voiceinteraction' died
I/ServiceManager(  249): service 'SecExternalDisplayService' died
I/ServiceManager(  249): service 'diskstats' died
I/ServiceManager(  249): service 'spengestureservice' died
I/ServiceManager(  249): service 'quickconnect' died
I/ServiceManager(  249): service 'samplingprofiler' died
I/ServiceManager(  249): service 'commontime_management' died
I/ServiceManager(  249): service 'dreams' died
I/ServiceManager(  249): service 'print' died
I/ServiceManager(  249): service 'restrictions' died
I/ServiceManager(  249): service 'media_session' died
I/ServiceManager(  249): service 'media_router' died
I/ServiceManager(  249): service 'trust' died
I/ServiceManager(  249): service 'fingerprint' died
I/ServiceManager(  249): service 'launcherapps' died
I/ServiceManager(  249): service 'voip' died
I/ServiceManager(  249): service 'media_projection' died
I/ServiceManager(  249): service 'imms' died
I/ServiceManager(  249): service 'connectivity' died
I/ServiceManager(  249): service 'sb_service' died
I/ServiceManager(  249): service 'clinfo' died
I/ServiceManager(  249): service 'servicediscovery' died
,I/ServiceManager(  249): service 'updatelock' died
I/ServiceManager(  249): service 'notification' died
I/ServiceManager(  249): service 'devicestoragemonitor' died
I/ServiceManager(  249): service 'location' died
I/ServiceManager(  249): service 'country_detector' died
I/ServiceManager(  249): service 'sec_location' died
,I/ServiceManager(  249): service 'search' died
I/ServiceManager(  249): service 'dropbox' died
I/ServiceManager(  249): service 'wallpaper' died
I/ServiceManager(  249): service 'audio' died
I/ServiceManager(  249): service 'rcp' died
,I/ServiceManager(  249): service 'input_method' died
I/ServiceManager(  249): service 'accessibility' died
I/ServiceManager(  249): service 'motion_recognition' died
I/ServiceManager(  249): service 'cover' died
I/ServiceManager(  249): service 'mount' died
I/ServiceManager(  249): service 'device_policy' died
,I/ServiceManager(  249): service 'harmony_eas_service' died
I/ServiceManager(  249): service 'sdp' died
I/ServiceManager(  249): service 'log_manager_service' died
I/ServiceManager(  249): service 'DockObserver' died
I/ServiceManager(  249): service 'usb' died
,I/ServiceManager(  249): service 'serial' died
I/ServiceManager(  249): service 'uimode' died
I/ServiceManager(  249): service 'jobscheduler' died
I/ServiceManager(  249): service 'batterystats' died
I/ServiceManager(  249): service 'appops' died
I/ServiceManager(  249): service 'power' died,
I/ServiceManager(  249): service 'display' died
I/ServiceManager(  249): service 'persona_policy' died
I/ServiceManager(  249): service 'entropy' died
W/AudioFlinger(  293): power manager service died !!!
I/ServiceManager(  249): service 'SEAMService' died,
W/AudioFlinger(  293): power manager service died !!!
I/ServiceManager(  249): service 'persona' died
I/ServiceManager(  249): service 'account' died
I/ServiceManager(  249): service 'content' died
I/ServiceManager(  249): service 'DirEncryptService' died
,I/ServiceManager(  249): service 'ReactiveService' died
I/ServiceManager(  249): service 'sedenial' died
I/ServiceManager(  249): service 'vibrator' died,
I/ServiceManager(  249): service 'tw_toolbox' died
I/ServiceManager(  249): service 'tima' died
I/ServiceManager(  249): service 'cepproxyks' died
I/ServiceManager(  249): service 'CustomFrequencyManagerService' died
I/ServiceManager(  249): service 'samsung.smartfaceservice' died
,I/ServiceManager(  249): service 'consumer_ir' died
I/ServiceManager(  249): service 'alarm' died
I/ServiceManager(  249): service 'enterprise_license_policy' died,
I/ServiceManager(  249): service 'context_aware' died
I/ServiceManager(  249): service 'scontext' died
I/ServiceManager(  249): service 'barbeam' died
I/ServiceManager(  249): service 'multiwindow_facade' died
,I/ServiceManager(  249): service 'window' died
I/ServiceManager(  249): service 'input' died
I/ServiceManager(  249): service 'lock_settings' died
I/ServiceManager(  249): service 'tactileassist' died,
I/ServiceManager(  249): service 'bluetooth_manager' died
I/ServiceManager(  249): service 'bluetooth_secure_mode_manager' died
,I/ServiceManager(  249): service 'dbinfo' died
I/ServiceManager(  249): service 'battery' died
I/ServiceManager(  249): service 'telephony.registry' died,
I/ServiceManager(  249): service 'meminfo' died
I/ServiceManager(  249): service 'permission' died
I/ServiceManager(  249): service 'activity' died
I/ServiceManager(  249): service 'cpuinfo' died
,I/ServiceManager(  249): service 'usagestats' died
I/ServiceManager(  249): service 'package' died
I/ServiceManager(  249): service 'edmnativehelper' died
I/ServiceManager(  249): service 'scheduling_policy' died
I/ServiceManager(  249): service 'procstats' died
I/ServiceManager(  249): service 'gfxinfo' died
I/ServiceManager(  249): service 'hardware' died
,I/ServiceManager(  249): service 'user' died
I/ServiceManager(  249): service 'webviewupdate' died
I/ServiceManager(  249): service 'sensorservice' died
I/ServiceManager(  249): service 'mdm.remotedesktop' died
I/SurfaceFlinger(  251): restart the boot-animation @ binderDied
E/audit_log( 2098): File locking failed. error= Bad file number
,W/Sensors ( 1171): sensorservice died [0xaefd5080]
W/Sensors ( 1474): sensorservice died [0xaefc73c0]
I/SurfaceFlinger(  251): id=2 Removed FocusedStackFrame (4/8)
I/SurfaceFlinger(  251): id=3 Removed DimLayer (0/7)
I/SurfaceFlinger(  251): id=4 Removed DimLayer (0/6)
I/SurfaceFlinger(  251): id=5 Removed DimLayer (0/5)
I/SurfaceFlinger(  251): id=6 Removed DimLayer (2/4)
,I/SurfaceFlinger(  251): id=2 Removed FocusedStackFrame (-2/4)
I/SurfaceFlinger(  251): id=3 Removed DimLayer (-2/4)
I/SurfaceFlinger(  251): id=4 Removed DimLayer (-2/4)
I/SurfaceFlinger(  251): id=5 Removed DimLayer (-2/4)
I/SurfaceFlinger(  251): id=6 Removed DimLayer (-2/4)
I/SurfaceFlinger(  251): id=7 Removed com.android.systemui.ImageWallpaper (0/3)
I/SurfaceFlinger(  251): id=7 Removed com.android.systemui.ImageWallpaper (-2/3)
,I/SurfaceFlinger(  251): id=18 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (0/2)
I/SurfaceFlinger(  251): id=9 Removed StatusBar (0/1)
I/SurfaceFlinger(  251): id=9 Removed StatusBar (-2/1)
I/SurfaceFlinger(  251): id=18 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/1)
,I/SurfaceFlinger(  251): id=14 Removed ColorFade (0/0)
I/SurfaceFlinger(  251): id=14 Removed ColorFade (-2/0)
W/Sensors ( 6024): sensorservice died [0xaeffb500]
W/Sensors ( 2180): sensorservice died [0xaefc0e80]
W/Sensors ( 1453): sensorservice died [0xaef7e340]
,E/WifiManager( 5611): Channel connection lost
E/WifiManager( 1453): Channel connection lost
E/WifiManager( 1171): Channel connection lost
E/WifiManager( 1304): Channel connection lost
F/libc    ( 8621): Fatal signal 7 (SIGBUS), code 2, fault addr 0x759a5bd8 in tid 8621 (p.assistantmenu)
E/WifiManager( 2180): Channel connection lost
F/libc    ( 8621): Unable to open connection to debuggerd: Connection refused
,D/SurfaceFlinger(  251): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  251): hwc_blank: Unblanking display: 0
W/Sensors ( 1304): sensorservice died [0x9d6212c0]
,W/Sensors ( 2210): sensorservice died [0xaef99bc0]
,W/Sensors ( 1441): sensorservice died [0xaef99b80]
,I/Zygote  (  317): Process 8621 exited due to signal (7)
,I/qdhwcomposer(  251): handle_blank_event: dpy:0 panel power state: 0
,F/libc    (  251): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb60a9268 in tid 251 (surfaceflinger)
,F/libc    (  251): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2098): File locking failed. error= Bad file number
,I/ServiceManager(  249): service 'SurfaceFlinger' died
I/ServiceManager(  249): service 'display.qservice' died
,W/SurfaceComposerClient( 3781): ComposerService remote (surfaceflinger) died [0xa1816180]
W/SurfaceComposerClient( 6473): ComposerService remote (surfaceflinger) died [0xaefcb700]
W/SurfaceComposerClient( 1171): ComposerService remote (surfaceflinger) died [0xaefd5340]
W/SurfaceComposerClient( 2251): ComposerService remote (surfaceflinger) died [0xaef67a80]
W/SurfaceComposerClient( 1474): ComposerService remote (surfaceflinger) died [0xaefc7280]
W/SurfaceComposerClient( 5611): ComposerService remote (surfaceflinger) died [0xaee21380]
,E/DisplayEventReceiver( 1171): Display event receiver pipe was closed or an error occurred.  events=0x9
,E/DisplayEventReceiver( 1474): Display event receiver pipe was closed or an error occurred.  events=0x9
,E/OpenGLRenderer( 1474): Display event receiver pipe was closed or an error occurred.  events=0x9
,E/DisplayEventReceiver( 6473): Display event receiver pipe was closed or an error occurred.  events=0x9
,E/OpenGLRenderer( 1171): Display event receiver pipe was closed or an error occurred.  events=0x9
,E/DisplayEventReceiver( 2251): Display event receiver pipe was closed or an error occurred.  events=0x9
,E/DisplayEventReceiver( 5611): Display event receiver pipe was closed or an error occurred.  events=0x9
E/DisplayEventReceiver( 3781): Display event receiver pipe was closed or an error occurred.  events=0x9

```
