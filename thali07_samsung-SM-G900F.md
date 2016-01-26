#### Test 5667282762e056f_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
I/BooksApp( 7273): Created application version: 3.3.11 (30311)
D/ResourcesManager( 2475): creating new AssetManager and set to /system/app/Books/Books.apk
,--------- beginning of system
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/BooksSync( 7273): Starting books sync, d
E/SQLiteLog( 7273): (284) automatic index on view_volumes(volume_id)
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 1691): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/HttpOperation( 6511): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6511): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6511): 	at kfv.a(PG:65)
E/HttpOperation( 6511): 	at kff.u(PG:385)
E/HttpOperation( 6511): 	at kfb.a(PG:29)
E/HttpOperation( 6511): 	at kff.l(PG:132)
E/HttpOperation( 6511): 	at dsf.a(PG:807)
E/HttpOperation( 6511): 	at fhk.a(PG:1126)
E/HttpOperation( 6511): 	at fhk.a(PG:908)
E/HttpOperation( 6511): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6511): 	at ihi.a(PG:22)
E/HttpOperation( 6511): 	at kft.a(PG:91)
E/HttpOperation( 6511): 	at kfv.a(PG:62)
E/HttpOperation( 6511): 	... 8 more
E/HttpOperation( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6511): 	at gde.c(Unknown Source)
E/HttpOperation( 6511): 	at gde.b(Unknown Source)
E/HttpOperation( 6511): 	at ihi.a(PG:19)
E/HttpOperation( 6511): 	... 10 more
D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 1691): creating new AssetManager and set to /system/app/Books/Books.apk
V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
D/AndroidRuntime( 7312): 
D/AndroidRuntime( 7312): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7312): CheckJNI is OFF
D/AndroidRuntime( 7312): setted country_code = Germany
D/AndroidRuntime( 7312): setted countryiso_code = DE
D/AndroidRuntime( 7312): setted sales_code = DBT
D/AndroidRuntime( 7312): readGMSProperty: start
D/AndroidRuntime( 7312): readGMSProperty: already setted!!
D/AndroidRuntime( 7312): readGMSProperty: end
D/AndroidRuntime( 7312): addProductProperty: start
I/art     ( 1691): Explicit concurrent mark sweep GC freed 21542(1254KB) AllocSpace objects, 3(243KB) LOS objects, 40% free, 17MB/29MB, paused 905us total 48.623ms
V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/GLSActivity( 1691): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1691): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1691): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1691): 	at android.os.Binder.execTransact(Binder.java:446)
D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/BooksAccountManager( 7273): Authentication error
E/BooksAccountManager( 7273): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7273): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7273): null auth token
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/System.out( 7273): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 7273): (HTTPLog)-Static: isShipBuild true
I/System.out( 7273): (HTTPLog)-Thread-1207-124251888: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/qtaguid ( 7273): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7273, getuid(): 10082
D/ResourcesManager( 1691): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
E/HttpOperation( 6511): [getaccountstatus] Unexpected exception
E/HttpOperation( 6511): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6511): 	at kfv.a(PG:65)
E/HttpOperation( 6511): 	at kff.u(PG:385)
E/HttpOperation( 6511): 	at kfb.a(PG:29)
E/HttpOperation( 6511): 	at ixd.a(PG:248)
E/HttpOperation( 6511): 	at ixd.b(PG:206)
E/HttpOperation( 6511): 	at ixd.a(PG:175)
E/HttpOperation( 6511): 	at fig.a(PG:78)
E/HttpOperation( 6511): 	at lex.a(PG:85)
E/HttpOperation( 6511): 	at lex.b(PG:132)
E/HttpOperation( 6511): 	at fhk.a(PG:1146)
E/HttpOperation( 6511): 	at fhk.a(PG:908)
E/HttpOperation( 6511): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6511): 	at ihi.a(PG:22)
E/HttpOperation( 6511): 	at kft.a(PG:91)
E/HttpOperation( 6511): 	at kfv.a(PG:62)
E/HttpOperation( 6511): 	... 12 more
E/HttpOperation( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6511): 	at gde.c(Unknown Source)
E/HttpOperation( 6511): 	at gde.b(Unknown Source)
E/HttpOperation( 6511): 	at ihi.a(PG:19)
E/HttpOperation( 6511): 	... 14 more
E/EsSyncAdapterService( 6511): Sync failure
E/EsSyncAdapterService( 6511): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6511): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6511): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6511): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6511): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6511): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6511): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6511): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6511): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6511): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6511): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6511): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6511): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6511): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6511): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6511): 	... 10 more
E/EsSyncAdapterService( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6511): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6511): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6511): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6511): 	... 12 more
E/EsSyncAdapterService( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6511): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6511): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6511): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6511): 	... 14 more
D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
E/SMD     (  283): DCD ON
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/AffinityControl( 7312): AffinityControl: registerfunction enter
D/AndroidRuntime( 7312): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  874): inState():  stateMachine is null !!
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  874): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  874): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/qtaguid ( 7273): Untagging socket 34
W/ApiaryClient( 7273): Error response from books API: {
W/ApiaryClient( 7273):  "error": {
W/ApiaryClient( 7273):   "errors": [
W/ApiaryClient( 7273):    {
W/ApiaryClient( 7273):     "domain": "global",
W/ApiaryClient( 7273):     "reason": "required",
W/ApiaryClient( 7273):     "message": "Login Required",
W/ApiaryClient( 7273):     "locationType": "header",
W/ApiaryClient( 7273):     "location": "Authorization"
W/ApiaryClient( 7273):    }
W/ApiaryClient( 7273):   ],
W/ApiaryClient( 7273):   "code": 401,
W/ApiaryClient( 7273):   "message": "Login Required"
W/ApiaryClient( 7273):  }
W/ApiaryClient( 7273): }
W/ApiaryClient( 7273): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7273): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3404731021516928865&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7273): Headers suppressed
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/art     (  874): Explicit concurrent mark sweep GC freed 53134(2MB) AllocSpace objects, 15(435KB) LOS objects, 30% free, 36MB/52MB, paused 1.829ms total 133.063ms
D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  874): mCursor = null
W/ActivityManager(  874): mDVFSHelper.acquire()
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7340): MountEmulatedStorage()
E/Zygote  ( 7340): v2
I/libpersona( 7340): KNOX_SDCARD checking this for 10200
I/libpersona( 7340): KNOX_SDCARD not a persona
I/SELinux ( 7340): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7340): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  874): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7340 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 7340): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/AndroidRuntime( 7312): Shutting down VM
D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  874): stay LED for fully charged
D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  874): Plugged
I/MotionRecognitionService(  874): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3244): Disconnected process message: 10
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/TimaKeyStoreProvider( 7340): TimaSignature is unavailable
D/ActivityThread( 7340): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/ActivityManager(  874): Display changed displayId=0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/8)
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
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
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SQLiteSecureOpenHelper( 3574): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3574): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 7340): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/SQLiteLog( 1691): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/HttpOperation( 6511): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6511): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6511): 	at kfv.a(PG:65)
E/HttpOperation( 6511): 	at kff.u(PG:385)
E/HttpOperation( 6511): 	at kfb.a(PG:29)
E/HttpOperation( 6511): 	at kff.l(PG:132)
E/HttpOperation( 6511): 	at dsf.a(PG:807)
E/HttpOperation( 6511): 	at fhk.a(PG:1126)
E/HttpOperation( 6511): 	at fhk.a(PG:908)
E/HttpOperation( 6511): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6511): 	at ihi.a(PG:22)
E/HttpOperation( 6511): 	at kft.a(PG:91)
E/HttpOperation( 6511): 	at kfv.a(PG:62)
E/HttpOperation( 6511): 	... 8 more
E/HttpOperation( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6511): 	at gde.c(Unknown Source)
E/HttpOperation( 6511): 	at gde.b(Unknown Source)
E/HttpOperation( 6511): 	at ihi.a(PG:19)
E/HttpOperation( 6511): 	... 10 more
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WebViewFactory( 7340): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7340): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7340): Loading: webviewchromium
I/LibraryLoader( 7340): Time to load native libraries: 2 ms (timestamps 9387-9389)
I/LibraryLoader( 7340): Expected native library version number "",actual native library version number ""
V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
E/HttpOperation( 6511): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6511): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6511): 	at kfv.a(PG:65)
E/HttpOperation( 6511): 	at kff.u(PG:385)
E/HttpOperation( 6511): 	at kfb.a(PG:29)
E/HttpOperation( 6511): 	at kff.l(PG:132)
E/HttpOperation( 6511): 	at ieo.a(PG:43)
E/HttpOperation( 6511): 	at iep.a(PG:93)
E/HttpOperation( 6511): 	at fhn.a(PG:59)
E/HttpOperation( 6511): 	at lex.a(PG:85)
E/HttpOperation( 6511): 	at lex.b(PG:132)
E/HttpOperation( 6511): 	at fhk.a(PG:1146)
E/HttpOperation( 6511): 	at fhk.a(PG:908)
E/HttpOperation( 6511): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6511): 	at ihi.a(PG:22)
E/HttpOperation( 6511): 	at kft.a(PG:91)
E/HttpOperation( 6511): 	at kfv.a(PG:62)
E/HttpOperation( 6511): 	... 12 more
E/HttpOperation( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6511): 	at gde.c(Unknown Source)
E/HttpOperation( 6511): 	at gde.b(Unknown Source)
E/HttpOperation( 6511): 	at ihi.a(PG:19)
E/HttpOperation( 6511): 	... 14 more
E/ExperimentLoader( 6511): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6511): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6511): 	at kfv.a(PG:65)
E/ExperimentLoader( 6511): 	at kff.u(PG:385)
E/ExperimentLoader( 6511): 	at kfb.a(PG:29)
E/ExperimentLoader( 6511): 	at kff.l(PG:132)
E/ExperimentLoader( 6511): 	at ieo.a(PG:43)
E/ExperimentLoader( 6511): 	at iep.a(PG:93)
E/ExperimentLoader( 6511): 	at fhn.a(PG:59)
E/ExperimentLoader( 6511): 	at lex.a(PG:85)
E/ExperimentLoader( 6511): 	at lex.b(PG:132)
E/ExperimentLoader( 6511): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6511): 	at fhk.a(PG:908)
E/ExperimentLoader( 6511): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6511): 	at ihi.a(PG:22)
E/ExperimentLoader( 6511): 	at kft.a(PG:91)
E/ExperimentLoader( 6511): 	at kfv.a(PG:62)
E/ExperimentLoader( 6511): 	... 12 more
E/ExperimentLoader( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6511): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6511): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6511): 	at ihi.a(PG:19)
E/ExperimentLoader( 6511): 	... 14 more
D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
V/WebViewChromiumFactoryProvider( 7340): Binding Chromium to main looper Looper (main, tid 1) {18ecbd8a}
I/LibraryLoader( 7340): Expected native library version number "",actual native library version number ""
I/chromium( 7340): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
I/BrowserStartupController( 7340): Initializing chromium process, renderers=0
W/art     ( 7340): Attempt to remove local handle scope entry from IRT, ignoring
I/PowerManagerService(  874): [PWL] Off : 15s ago
I/PowerManagerService(  874): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  874): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  874): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=2475, ws=null) (elapsedTime=52206)
I/PowerManagerService(  874): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=874, ws=WorkSource{10082}) (elapsedTime=1936)
I/PowerManagerService(  874): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.plus.content.EsProvider/com.google/eM_ADDR' (uid=1000, pid=874, ws=WorkSource{10135}) (elapsedTime=801)
I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/chromium( 7340): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7340): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7340): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
I/Adreno-EGL( 7340): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7340): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7340): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7340): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7340): Remote Branch: 
I/Adreno-EGL( 7340): Local Patches: 
I/Adreno-EGL( 7340): Reconstruct Branch: 
D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/HttpOperation( 6511): [getaccountstatus] Unexpected exception
E/HttpOperation( 6511): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6511): 	at kfv.a(PG:65)
E/HttpOperation( 6511): 	at kff.u(PG:385)
E/HttpOperation( 6511): 	at kfb.a(PG:29)
E/HttpOperation( 6511): 	at ixd.a(PG:248)
E/HttpOperation( 6511): 	at ixd.b(PG:206)
E/HttpOperation( 6511): 	at ixd.a(PG:175)
E/HttpOperation( 6511): 	at fig.a(PG:78)
E/HttpOperation( 6511): 	at lex.a(PG:85)
E/HttpOperation( 6511): 	at lex.b(PG:132)
E/HttpOperation( 6511): 	at fhk.a(PG:1146)
E/HttpOperation( 6511): 	at fhk.a(PG:908)
E/HttpOperation( 6511): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6511): 	at ihi.a(PG:22)
E/HttpOperation( 6511): 	at kft.a(PG:91)
E/HttpOperation( 6511): 	at kfv.a(PG:62)
E/HttpOperation( 6511): 	... 12 more
E/HttpOperation( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6511): 	at gde.c(Unknown Source)
E/HttpOperation( 6511): 	at gde.b(Unknown Source)
E/HttpOperation( 6511): 	at ihi.a(PG:19)
E/HttpOperation( 6511): 	... 14 more
E/EsSyncAdapterService( 6511): Sync failure
E/EsSyncAdapterService( 6511): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6511): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6511): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6511): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6511): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6511): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6511): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6511): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6511): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6511): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6511): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6511): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6511): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6511): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6511): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6511): 	... 10 more
E/EsSyncAdapterService( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6511): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6511): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6511): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6511): 	... 12 more
E/EsSyncAdapterService( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6511): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6511): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6511): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6511): 	... 14 more
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
D/SyncManager(  874): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 31283, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ActivityManager(  874): Activity pause timeout for ActivityRecord{948446b u0 com.test.thalitest/.MainActivity t18}
W/chromium( 7340): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7340): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/art     ( 7340): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7340): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7340): CordovaWebView is running on device made by: samsung
W/art     ( 7340): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7340): Attempt to remove local handle scope entry from IRT, ignoring
D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  874): mCursor = null
D/Activity( 7340): performCreate Call secproduct feature valuefalse
D/Activity( 7340): performCreate Call debug elastic valuetrue
V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/OpenGLRenderer( 7340): Render dirty regions requested: true
D/ActivityManager(  874): post active user change for 0
D/KnoxTimeoutHandler(  874): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  874): handleActiveUserChange for user 0
I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/StatusBarManagerService(  874): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/StatusBarManagerService(  874): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/OpenGLRenderer( 7340): Initialized EGL, version 1.4
D/ResourcesManager( 1691): creating new AssetManager and set to /system/app/Books/Books.apk
V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
I/OpenGLRenderer( 7340): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
D/OpenGLRenderer( 7340): Enabling debug mode 0
D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/GLSActivity( 1691): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1691): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1691): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1691): 	at android.os.Binder.execTransact(Binder.java:446)
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
E/BooksAccountManager( 7273): Authentication error
E/BooksAccountManager( 7273): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7273): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7273): null auth token
I/qtaguid ( 7273): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7273, getuid(): 10082
I/qtaguid ( 7273): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7273, getuid(): 10082
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/InputMethodManagerService(  874): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/ActivityManager(  874): mDVFSHelper.release()
I/Timeline(  874): Timeline: Activity_windows_visible id: ActivityRecord{948446b u0 com.test.thalitest/.MainActivity t18} time:90031
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/IInputConnectionWrapper( 7340): showStatusIcon on inactive InputConnection
I/Timeline( 7340): Timeline: Activity_idle id: android.os.BinderProxy@366ec65 time:90039
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/qtaguid ( 7273): Untagging socket 34
,W/ApiaryClient( 7273): Error response from books API: {
W/ApiaryClient( 7273):  "error": {
W/ApiaryClient( 7273):   "errors": [
W/ApiaryClient( 7273):    {
W/ApiaryClient( 7273):     "domain": "global",
W/ApiaryClient( 7273):     "reason": "required",
W/ApiaryClient( 7273):     "message": "Login Required",
W/ApiaryClient( 7273):     "locationType": "header",
W/ApiaryClient( 7273):     "location": "Authorization"
W/ApiaryClient( 7273):    }
W/ApiaryClient( 7273):   ],
W/ApiaryClient( 7273):   "code": 401,
W/ApiaryClient( 7273):   "message": "Login Required"
W/ApiaryClient( 7273):  }
W/ApiaryClient( 7273): }
,W/ApiaryClient( 7273): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7273): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3404731021516928865&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7273): Headers suppressed
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1691): (10) POSIX Error : 11 SQLite Error : 3850
,I/chromium( 7340): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7340): 
,D/JsMessageQueue( 7340): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7340): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258327168
,I/chromium( 7340): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1691): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1691): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1691): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1691): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7273): Authentication error
E/BooksAccountManager( 7273): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7273): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7273): null auth token
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/qtaguid ( 7273): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7273, getuid(): 10082
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,I/qtaguid ( 7273): Untagging socket 34
,W/ApiaryClient( 7273): Error response from books API: {
W/ApiaryClient( 7273):  "error": {
W/ApiaryClient( 7273):   "errors": [
W/ApiaryClient( 7273):    {
W/ApiaryClient( 7273):     "domain": "global",
W/ApiaryClient( 7273):     "reason": "required",
W/ApiaryClient( 7273):     "message": "Login Required",
W/ApiaryClient( 7273):     "locationType": "header",
W/ApiaryClient( 7273):     "location": "Authorization"
W/ApiaryClient( 7273):    }
W/ApiaryClient( 7273):   ],
W/ApiaryClient( 7273):   "code": 401,
W/ApiaryClient( 7273):   "message": "Login Required"
W/ApiaryClient( 7273):  }
W/ApiaryClient( 7273): }
,W/ApiaryClient( 7273): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7273): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3404731021516928865&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7273): Headers suppressed
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  283): DCD ON
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/BooksSync( 7273): Soft error
E/BooksSync( 7273): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7273): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3404731021516928865&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7273): Headers suppressed
E/BooksSync( 7273): 
E/BooksSync( 7273): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7273): Sync error
E/BooksSync( 7273): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7273): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3404731021516928865&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7273): Headers suppressed
E/BooksSync( 7273): 
E/BooksSync( 7273): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7273): Finished books sync
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  874): Killing 4913:com.android.providers.calendar/u0a46 (adj 15): bgCount ##41
,D/SyncManager(  874): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 64183, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  874): mCursor = null
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  874): failed to open /acct/uid_10046/pid_4913/cgroup.procs: No such file or directory
,I/art     ( 7340): Background sticky concurrent mark sweep GC freed 66029(7MB) AllocSpace objects, 3(4MB) LOS objects, 23% free, 25MB/33MB, paused 1.740ms total 106.259ms
,I/GAV2    ( 7273): Thread[GAThread,5,main]: No campaign data found.
,W/jxcore-log( 7340): Initializing JXcore engine
,W/jxcore-log( 7340): JXcore engine is ready
,E/auditd  ( 2086): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  874): Got Modify Event and sending Denial Intent foraudit.log
,D/SecurityLogAgent:SEDenialService(  874): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,W/jxcore-log( 7340): Starting JXcore engine
,E/Zygote  ( 7434): MountEmulatedStorage()
E/Zygote  ( 7434): v2
I/libpersona( 7434): KNOX_SDCARD checking this for 1000
I/libpersona( 7434): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7434 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7434): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7434): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7434): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/jxcore-log( 7340): Platform android
W/jxcore-log( 7340): 
,W/jxcore-log( 7340): Process ARCH arm
W/jxcore-log( 7340): 
,D/TimaKeyStoreProvider( 7434): TimaSignature is unavailable
,D/ActivityThread( 7434): Added TimaKeyStore provider
,D/ResourcesManager( 7434): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7434):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7434):  SeDenialReceiver : File path = null
,I/ActivityManager(  874): Killing 6659:com.sec.android.app.videoplayer/u0a54 (adj 15): bgCount ##41
,W/libprocessgroup(  874): failed to open /acct/uid_10054/pid_6659/cgroup.procs: No such file or directory
,I/jxcore-log( 7340): JXcore Cordova bridge is ready!
I/jxcore-log( 7340): 
,W/jxcore-log( 7340): JXcore engine is started
,I/jxcore-log( 7340): Toggling radios to true
I/jxcore-log( 7340): 
,D/BluetoothAdapter( 7340): enable()
,D/BluetoothAdapter( 7340): enable(): BT is already enabled..!
,D/WifiService(  874): New client listening to asynchronous messages
,I/WifiManager( 7340): packageName : com.test.thalitest
,D/SecContentProvider(  874): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  874): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  874): mCursor = null
,D/WifiService(  874): setWifiEnabled: true pid=7340, uid=10200
,E/WifiService(  874): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  874): Permission Denial: getCurrentUser() from pid=7340, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  874): Failed getting userId using ActivityManagerNative
W/WifiService(  874): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7340, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  874): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  874): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  874): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  874): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  874): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  874): name = wifi_on
,I/WifiService(  874): disconnect: pid=7340, uid=10200
,I/wpa_supplicant( 1275): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7340): Radios toggled
I/jxcore-log( 7340): 
,I/jxcore-log( 7340): My device name is: samsung-SM-G900F
I/jxcore-log( 7340): 
,I/wpa_supplicant( 1275): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1275): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1275): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1275): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  874): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1275): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1275): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1275): Disconnected - do not scan
I/wpa_supplicant( 1275): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  874): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  874): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  874): handleNetworkDisconnect "NG700" nid=0
,E/WifiConfigStore(  874): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  874): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  874): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  874): do suspend true
,D/WifiP2pService(  874): InactiveState{ what=143375 }
,D/WifiP2pService(  874): P2pEnabledState{ what=143375 }
,V/AlarmManager(  874): waitForAlarm result :4
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  276): Clearing all IP addresses on wlan0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
V/NativeCrypto( 1691): Read error: ssl=0xab433600: I/O error during system call, Connection timed out
E/Zygote  ( 7453): MountEmulatedStorage()
E/Zygote  ( 7453): v2
I/libpersona( 7453): KNOX_SDCARD checking this for 10179
I/libpersona( 7453): KNOX_SDCARD not a persona
I/ActivityManager(  874): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7453 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
V/NativeCrypto( 1691): SSL shutdown failed: ssl=0xab433600: I/O error during system call, Broken pipe
,I/SELinux ( 7453): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7453): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7453): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/WifiStateMachine(  874): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService(  874): updateNetworkInfo()
D/ConnectivityService(  874): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  874): updateNetworkInfo()
D/ConnectivityService(  874): ignoring duplicate network state non-change
D/ConnectivityService(  874): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
E/WifiConfigStore(  874): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/WifiTrafficPoller(  874): evaluateTrafficStatsPolling
,I/CLocInfoService(  874): External Intent Received android.net.wifi.STATE_CHANGE
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine(  874): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1275): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1275): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1275): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1275): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1275): First Scan Start
D/ConnectivityService(  874): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
E/WifiStateMachine(  874): ConnectModeState: Network connection lost 
I/wpa_supplicant( 1275): Scan requested (ret=0) - scan timeout 30 seconds
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): DefaultState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): Validated
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
E/WifiStateMachine(  874): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  874): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
E/WifiStateMachine(  874): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  874): do suspend true
D/WifiP2pService(  874): InactiveState{ what=143375 }
D/WifiP2pService(  874): P2pEnabledState{ what=143375 }
D/TimaKeyStoreProvider( 7453): TimaSignature is unavailable
D/ActivityThread( 7453): Added TimaKeyStore provider
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ResourcesManager( 7453): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
W/ResourcesManager( 7453): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/CommandListener(  276): Clearing all IP addresses on wlan0
D/ConnectivityService(  874): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  874): calling update connectivity
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  874): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  874): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/EntConnectivity(  874): Not allowed due to - mEnabled false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524292
E/WifiStateMachine(  874): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiStateMachine(  874): updateConfiguredNetworkExpiration - currTime: 1453830955208
D/WifiStateMachine(  874): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine(  874): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  874): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiNetworkAgent(  874): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  874): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  874): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/WifiTrafficPoller(  874): evaluateTrafficStatsPolling
D/CSLegacyTypeTracker(  874): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  874): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  874): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1474): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/CLocInfoService(  874): External Intent Received android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  874): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  874): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  874): setDetailed state send new extra info"NG700"
D/SecContentProvider2(  874): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  874): mCursor = null
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  874): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  874): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  874): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  874): getSBEnabled() enabled =false
D/SmartBondingService(  874): getSBEnabled() enabled =false
D/SmartBondingService(  874): getSBEnabled() enabled =false
V/NetworkStats(  874): updateIfacesLocked()
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
V/NetworkStats(  874): performPollLocked(flags=0x1)
D/NetworkStatsFactory(  874): UpdateStatsForKnox
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
D/SmartBondingService(  874): getNetworkEnabled : wifi : true mobile : true
D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
E/ConnectivityService(  874): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
V/NetworkStats(  874): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
V/NetworkStats(  874): performPollLocked() took 14ms
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
D/SecContentProvider2(  874): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  874): mCursor = null
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/UMC:Core( 7453): onCreate(): 
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/USER_AGENT( 7453): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
,D/[SAMSUNG SMARCART NATIVE]( 7453): initialize...
,D/[SAMSUNG SMARCART NATIVE]( 7453): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/CSTORAGE( 7453): ================================================
,I/CSTORAGE( 7453):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 7453): ================================================
I/TZ_CCM_C_GetFunctionList: ( 7453): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 7453): FINISHED: initialize rv:0
,D/UMC:SecurityUtils( 7453): Loaded server certificates: 0
,D/UMC:SecurityUtils( 7453): Loaded server certificates: 0
,D/UMC:SecurityUtils( 7453): timaVersion on the device: 3.0
,D/UMC:CloudMDMSecurity( 7453): New Flow
,D/TimaService(  874): TIMA3: in ccmRegisterForDefaultCertificate
,D/TimaService(  874): TIMA: in getTimaVersion
I/        (  874): CCM JNI: In ccm_register_for_default_cert
I/        (  874): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  874): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
,I/TZ_CCM_C_Initialize: (  874): pInitArgs 0x96b31814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  874): &ctx = 0x9feb2c1c
I/TLC_TZ_CCM: (  874): creating new ccm context...
I/TLC_TZ_CCM: (  874): initializing ccm context...
I/TLC_TZ_CCM: (  874): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  874): process = tz_ccm, process_strlen = 6
,I/TZ: client_server_communication(  874): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  874): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  874): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  874): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  874): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  874): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  874): Client_Server_Open was called
,I/TZ: client_server_communication(  874): IClientServer::IClientServer()
I/TZ: client_server_communication(  874): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  874): IClientServer::~IClientServer()
,I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 1077): OPENSWCONN
I/TZ_CCM_SERVER( 1077): creating new ccm context...
I/TZ_CCM_SERVER( 1077): initializing ccm context...
I/TZ_CCM_SERVER( 1077): root = /firmware/image, root_strlen = 15
I/TZ_CCM_SERVER( 1077): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1077): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1077): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1077): aligned max_sendmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1077): aligned max_recvmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1077): max_message_size = 38912 = 0x9800
D/QSEECOMAPI: ( 1077): QSEECom_get_handle sb_length = 0x9800
,D/QSEECOMAPI: ( 1077): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1077): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication( 1077): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
,I/TZ: client_server_communication(  874): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  874): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  874): ctx = 0x92ddb5f0, comm = 0x6e5156a0, sendmsg = 0x6ff30000, recvmsg = 0x6ff34c00
I/TZ_init: (  874): TZ_init: sending initialization request...
,I/TZ: client_server_communication(  874): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  874): Calling Communicate()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
,I/TZ_init: (  874): TZ_init: successful initialization
,I/TLC_TZ_COMMON: key_db_init: (  874): Exercising TZ_DB_INIT in TLC
,I/TZ: client_server_communication(  874): Cmd id = 17, len = 19456
I/TZ: client_server_communication(  874): Calling Communicate()
,I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
,I/TZ_COMMON: tlc_key_db_util: (  874): DB Operation suceeded
,I/TLC_TZ_CCM: register for default cert: (  874): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  874): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  874): Calling Communicate()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
,I/TLC_TZ_CCM: register for default cert: (  874): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: (  874): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  874): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
,I/TZ: client_server_communication(  874): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  874): Calling Communicate()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
,I/TZ: client_server_communication(  874): Client_Server_Close was called
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1077): CLOSESWCONN
D/QSEECOMAPI: ( 1077): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1077): QSEECom_shutdown_app, app_id = 4
I/TZ: client_server_communication(  874): Client_Server_Close succeeded
D/UMC:CloudMDMSecurity( 7453): ccmRegisterForDefaultCertificate: 0
D/UMC:CloudMDMSecurity( 7453): TIMA service call for password change success!!
,D/UMC:AdminManager( 7453): init - start
,D/UMC:AdminManager( 7453): loadAdmins
,D/SSRM:m  (  874): SIOP:: AP = 380, PST = 428, CUR = 300
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/UMC:AdminManager( 7453): startPolicyHandlers
,I/UMC:TestPolicyHandler( 7453): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 7453): init - end
,V/UMC:AlarmHandler( 7453): Enter loadList
,D/GSLBManager( 7453): migrateStoredUrlFromOldPref
,D/GSLBManager( 7453): migrateStoredUrlFromOldPref : Migration Not Needed
,D/UMC:UMCAdmin( 7453): deactivateUMCAdminIfNotRequired : -1
E/UMC:Utils( 7453): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 7453): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 7453): isContainer : 0
,W/LicenseLogService(  874): log() failed
,D/EnterpriseDeviceManagerService(  874): isManagedProfileUser(): userId = 0
,E/UMC:UMCAdmin( 7453): No active admin owned by uid 10179
D/UMC:UMCAdmin( 7453): isContainer : 0
D/UMC:UMCAdmin( 7453): deactivateUMCAdmin - UMC App Admin deactivated
V/UMC:AlarmHandler( 7453): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
D/QuickStartReceiver( 7453): Msg Id : 2
D/QuickStartReceiver( 7453): model : SM-G900F
D/QuickStartReceiver( 7453): id : 100
I/ActivityManager(  874): Killing 5878:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
I/Hs20UtilService( 1300): Starting #6
I/Hs20UtilService( 1300): Message received 5007
D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1300): MountReceiver.mPrefHandler - 7002
I/Hs20UtilService( 1300): Starting #7
I/Hs20UtilService( 1300): Message received 5007
D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1300): MountReceiver.mPrefHandler - 7002
,W/libprocessgroup(  874): failed to open /acct/uid_1000/pid_5878/cgroup.procs: No such file or directory
,D/ConnectivityService(  874): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  874): updateDataUsageMap
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2244): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  874): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  874): MasterInitialState.processMessage what=3
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  874): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  874): CLoinfo wifi false
D/SmartBondingService(  874): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  874): getSBEnabled() enabled =false
D/SmartBondingService(  874): getSBEnabled() enabled =false
D/SmartBondingService(  874): getSBEnabled() enabled =false
,W/SLocation(  874): No Active Data Connection
,D/SmartBondingService(  874): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5376): type=WIFI subType= reason=null isConnected=false
,I/DBG_DM  ( 3812): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/PCWCLIENTTRACE_PushUtil( 6746): SPPPushClient is installed : true
,I/SystemBroadcastReceiver( 7130): [#DCM#] [DCM_Performance] onReceive completed in time  268 microsec. 
,I/PCWCLIENTTRACE_PushUtil( 6746): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6746): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6746): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6746): noConnectivity : true
I/SystemBroadcastReceiver( 7130): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7130): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7130): [#DCM#] setIsConnectedForExtractors 
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3812): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7506): MountEmulatedStorage()
,E/Zygote  ( 7506): v2
I/libpersona( 7506): KNOX_SDCARD checking this for 10002
I/libpersona( 7506): KNOX_SDCARD not a persona
,E/SMD     (  283): DCD ON
,I/ActivityManager(  874): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7506 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 274us total 11.739ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 7.923ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.886ms
,I/SELinux ( 7506): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7506): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7506): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7506): TimaSignature is unavailable
,D/ActivityThread( 7506): Added TimaKeyStore provider
,D/ResourcesManager( 7506): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  874): Killing 6208:com.sec.providers.settingsearch/u0a168 (adj 15): bgCount ##41
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7523): MountEmulatedStorage()
I/libpersona( 7523): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7523): v2
I/libpersona( 7523): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7523 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7523): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7523): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7523): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7523): TimaSignature is unavailable
,D/ActivityThread( 7523): Added TimaKeyStore provider
,D/ResourcesManager( 7523): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  874): failed to open /acct/uid_10168/pid_6208/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7523): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7523): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7523): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7523): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7523): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7523): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7542): MountEmulatedStorage()
,E/Zygote  ( 7542): v2
I/libpersona( 7542): KNOX_SDCARD checking this for 10011
I/libpersona( 7542): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7542 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7542): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7542): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7542): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1275): nl80211: Received scan results (2 BSSes)
I/wpa_supplicant( 1275): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1275): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1275): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1275): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
E/WifiStateMachine(  874): [1,453,830,956,248 ms] noteScanEnd no scan source
,E/WifiStateMachine(  874): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1782a39a sup_state=SCANNING debouncing=false
,I/CLocInfoService(  874): External Intent Received android.net.wifi.SCAN_RESULTS
,E/WifiStateMachine(  874): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  874): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  874): setDetailed state send new extra info0x
,D/SecContentProvider2(  874): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  874): mCursor = null
,D/TimaKeyStoreProvider( 7542): TimaSignature is unavailable
,D/ActivityThread( 7542): Added TimaKeyStore provider
,D/ResourcesManager( 7542): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  874): Killing 6712:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,I/wpa_supplicant( 1275): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1275): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1275): Associated with C0.AA.48
,E/WifiStateMachine(  874): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  874): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  874): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  874): mCursor = null
,I/FOTA_Client( 7542): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7542): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/wpa_supplicant( 1275): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1275): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  874): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  874): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  874): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  874): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  874): mCursor = null
,I/wpa_supplicant( 1275): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1275): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1275): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  874): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  874): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 1275): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1275): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1275): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1275): Blacklist: Clear (temp) 
I/wpa_supplicant( 1275): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
I/FOTA_Client( 7542): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/WifiStateMachine(  874): Network connection established
I/FOTA_Client( 7542): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,D/WifiNative-HAL(  874): callSECApiVoid - ID [50]
E/WifiStateMachine(  874): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  874): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  874): External Intent Received android.net.wifi.STATE_CHANGE
,I/FOTA_Client( 7542): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,D/ConnectivityService(  874): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  874): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  874): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  874): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  874): Got NetworkAgent Messenger
D/ConnectivityService(  874): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  874): updateNetworkInfo()
D/ConnectivityService(  874): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  874): NetworkAgent connected
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  874): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  874): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  874): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  874): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/libprocessgroup(  874): failed to open /acct/uid_10015/pid_6712/cgroup.procs: No such file or directory
,E/Zygote  ( 7563): MountEmulatedStorage()
E/Zygote  ( 7563): v2
I/libpersona( 7563): KNOX_SDCARD checking this for 10019
I/libpersona( 7563): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7563 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 6731:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,D/CommandListener(  276): Setting iface cfg
,E/WifiStateMachine(  874): Start Dhcp Watchdog 2
,D/SecContentProvider2(  874): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  874): mCursor = null
,E/WifiStateMachine(  874): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  874): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  874): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/SELinux ( 7563): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7563): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7563): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7563): TimaSignature is unavailable
,D/ActivityThread( 7563): Added TimaKeyStore provider
,W/libprocessgroup(  874): failed to open /acct/uid_10016/pid_6731/cgroup.procs: No such file or directory
,D/ResourcesManager( 7563): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7563): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7563): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453830956460
,I/KLMS-2.4.503: ( 7563): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7563): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7563): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  874): Killing 6418:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  874): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  874): do suspend false
,D/SecContentProvider2(  874): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  874): mCursor = null
D/WifiP2pService(  874): InactiveState{ what=143375 }
,D/WifiP2pService(  874): P2pEnabledState{ what=143375 }
,E/Zygote  ( 7580): MountEmulatedStorage()
E/Zygote  ( 7580): v2
I/libpersona( 7580): KNOX_SDCARD checking this for 10037
I/libpersona( 7580): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7580 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7580): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7580): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7580): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7580): TimaSignature is unavailable
,D/ActivityThread( 7580): Added TimaKeyStore provider
,D/ResourcesManager( 7580): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7580): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,W/libprocessgroup(  874): failed to open /acct/uid_10034/pid_6418/cgroup.procs: No such file or directory
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5257): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6791): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6791): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6791): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6791): [SLFUCHKMGR] constructor called
,I/SA      ( 6791): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6791): [OR] == isSIMCardReady false ==
,I/SA      ( 6791): [SCU] == networkStateCheck == false
,I/SA      ( 6791): [OR] onReceive END
,E/SPPClientService( 5257): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7597): MountEmulatedStorage()
,E/Zygote  ( 7597): v2
I/libpersona( 7597): KNOX_SDCARD checking this for 10071
I/libpersona( 7597): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7597 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7597): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7597): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7597): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  874): Killing 4735:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7597): TimaSignature is unavailable
,D/ActivityThread( 7597): Added TimaKeyStore provider
,D/ResourcesManager( 7597): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,E/dhcpcd  ( 7615): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,W/ResourcesManager( 7597): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7597): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/dhcpcd  ( 7615): version 5.5.6 starting
E/dhcpcd  ( 7615): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,W/ResourcesManager( 7597): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7597): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7597): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7597): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7597): [KK AccuPhone]>>> ==============================================================================================
,W/libprocessgroup(  874): failed to open /acct/uid_10035/pid_4735/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7615): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7615): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7615): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7615): bssid match
,D/comsamsunglog( 7597): [KK AccuPhone]>>> ==============================================================================================
I/dhcpcd  ( 7615): wlan0: rebinding lease of 192.168.1.135
,D/comsamsunglog( 7597): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7597): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7597): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  874): name = aw_daemon_service_key_agree_popup_check
,D/SettingsProvider(  874): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  874): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  874): selectionArgs: false
D/SettingsProvider(  874): selectionArgs: 10071
,D/SecContentProvider(  874): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  874): ret = -1
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7597): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7597): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7597): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7597): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7597): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7597): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7597): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7597): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7597): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7597): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7629): MountEmulatedStorage()
I/libpersona( 7629): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7629): v2
I/libpersona( 7629): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7629 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 6040:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/SELinux ( 7629): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7629): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7629): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7629): TimaSignature is unavailable
,D/ActivityThread( 7629): Added TimaKeyStore provider
,D/ResourcesManager( 7629): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7629): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  874): failed to open /acct/uid_10042/pid_6040/cgroup.procs: No such file or directory
,I/KnoxUsageLogPro( 7629): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7629): premStatus:2
,I/KnoxUsageLogPro( 7629): isEulaShown : false
I/KnoxUsageLogPro( 7629): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7644): MountEmulatedStorage()
,E/Zygote  ( 7644): v2
I/libpersona( 7644): KNOX_SDCARD checking this for 10088
I/libpersona( 7644): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7644 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 5680:com.android.mms/u0a50 (adj 15): bgCount ##41
,I/SELinux ( 7644): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/CountryDetector(  874): No listener is left
I/SELinux ( 7644): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7644): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7644): TimaSignature is unavailable
,D/ActivityThread( 7644): Added TimaKeyStore provider
,D/ResourcesManager( 7644): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  874): failed to open /acct/uid_10050/pid_5680/cgroup.procs: No such file or directory
,I/ActivityManager(  874): Killing 6815:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,D/Headlines( 5520): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5520): getCountryCode(): countryCode = DE
,D/Headlines( 5520): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5520): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5520): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5520): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5520): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5520): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5520): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7661): MountEmulatedStorage()
E/Zygote  ( 7661): v2
I/libpersona( 7661): KNOX_SDCARD checking this for 10128
I/libpersona( 7661): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7661 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7661): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7661): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7661): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7661): TimaSignature is unavailable
,D/ActivityThread( 7661): Added TimaKeyStore provider
,D/ResourcesManager( 7661): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  874): failed to open /acct/uid_10051/pid_6815/cgroup.procs: No such file or directory
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7661): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7661): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7661): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7661): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7661): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7661): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7661): Loading: webviewchromium
,I/LibraryLoader( 7661): Time to load native libraries: 4 ms (timestamps 6283-6287)
,I/LibraryLoader( 7661): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7661): Binding Chromium to main looper Looper (main, tid 1) {3c265cd8}
,I/LibraryLoader( 7661): Expected native library version number "",actual native library version number ""
,I/chromium( 7661): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7661): Initializing chromium process, renderers=0
,W/art     ( 7661): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7661): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7661): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7661): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7661): Requires BLUETOOTH permission
,I/Adreno-EGL( 7661): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7661): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7661): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7661): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7661): Remote Branch: 
I/Adreno-EGL( 7661): Local Patches: 
I/Adreno-EGL( 7661): Reconstruct Branch: 
,I/NSApplication( 7661): Starting up...
,I/dhcpcd  ( 7615): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7615): wlan0: leased 192.168.1.135 for 86400 seconds
,E/Zygote  ( 7719): MountEmulatedStorage()
E/Zygote  ( 7719): v2
I/libpersona( 7719): KNOX_SDCARD checking this for 10138
I/libpersona( 7719): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7719 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 6835:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,E/WifiStateMachine(  874): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  874): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/ConnectivityService(  874): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/SELinux ( 7719): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7719): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7719): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7719): TimaSignature is unavailable
,D/ActivityThread( 7719): Added TimaKeyStore provider
,D/ResourcesManager( 7719): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/libprocessgroup(  874): failed to open /acct/uid_10058/pid_6835/cgroup.procs: No such file or directory
,W/ResourcesManager( 7719): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7719): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7719): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/WifiStateMachine(  874): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  874): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  874): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/QuickConnect( 7719): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7719): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7719): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7758): MountEmulatedStorage()
I/libpersona( 7758): KNOX_SDCARD checking this for 10163
E/Zygote  ( 7758): v2
I/libpersona( 7758): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7758 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 6228:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SELinux ( 7758): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7758): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7758): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  874): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  874): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  874): do suspend true
,W/libprocessgroup(  874): failed to open /acct/uid_1000/pid_6228/cgroup.procs: No such file or directory
,D/WifiP2pService(  874): InactiveState{ what=143375 }
,D/WifiP2pService(  874): P2pEnabledState{ what=143375 }
,D/TimaKeyStoreProvider( 7758): TimaSignature is unavailable
,E/WifiStateMachine(  874): WifiStateMachine DHCP successful
,D/ActivityThread( 7758): Added TimaKeyStore provider
,E/WifiStateMachine(  874): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  874): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  874): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  874): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  874): Not connected state, yet.
E/WifiStateMachine(  874): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  874): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  874): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  874): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  874): callSECApiInt - ID [210]
,E/WifiStateMachine(  874): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  874): updateNetworkInfo()
,D/ConnectivityService(  874): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  874): Adding iface wlan0 to network 503
,I/CLocInfoService(  874): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  874): updateDnsLinkProperty: enter
W/ResourcesManager( 7758): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/ResourcesManager( 7758): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ResourcesManager( 7758): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/WifiWatchdogStateMachine.DnsPinger(  874): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
W/ResourcesManager( 7758): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/WifiWatchdogStateMachine.DnsResolver(  874): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
W/ResourcesManager( 7758): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/WifiWatchdogStateMachine.SingDnsChecker(  874): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  874): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  874): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  874): Now, connected state.
E/WifiStateMachine(  874): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  874): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
E/WifiStateMachine(  874): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  874): evaluateTrafficStatsPolling
,I/CLocInfoService(  874): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiTrafficPoller(  874): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  874): mBoosterFLAG : 0
D/ConnectivityService(  874): Adding Route [fe80::/64 -> :: wlan0] to network 503
I/WifiTrafficPoller(  874): current booster mode : FullMode
,D/ConnectivityService(  874): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/WifiNative-HAL(  874): callSECApiVoid - ID [212]
,D/ConnectivityService(  874): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  874): Unexpected mtu value: 0, wlan0
,I/CLocInfoService(  874): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  874): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  874): updateSourceRoutes : add src route for:192.168.1.135
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,V/        (  276): QcRouteController
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/WifiStateMachine(  874): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine(  874): REQUEST_POWER_SAVE_ON
,V/        (  276): QcRouteController
,V/        (  276): QcRouteController
,V/        (  276): QcRouteController
,V/        (  276): QcRouteController
,D/RCPManagerService(  874): exchangeData() failure , invalid userId
,V/        (  276): QcRouteController
,V/        (  276): QcRouteController
,D/RCPManagerService(  874): exchangeData() failure , invalid userId
,D/RCPManagerService(  874): exchangeData() failure , invalid userId
,V/        (  276): QcRouteController
,D/ConnectivityService(  874): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  276): QcRouteController
,V/        (  276): QcRouteController
,D/RCPManagerService(  874): exchangeData() failure , invalid userId
,W/NetworkManagementService(  874): route cmd failed: 
W/NetworkManagementService(  874): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 68 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  874): '
W/NetworkManagementService(  874): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  874): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  874): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  874): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  874): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  874): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  874): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  874): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:5997)
W/NetworkManagementService(  874): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  874): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2337)
W/NetworkManagementService(  874): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  874): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  874): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ConnectivityService(  874): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  874): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  874): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  874): calling update connectivity
D/ConnectivityService(  874): ignoring duplicate network state non-change
E/ConnectivityService(  874): updateNetworkInfo()
E/ConnectivityService(  874): updateNetworkInfo()
D/ConnectivityService(  874): ignoring duplicate network state non-change
,D/ConnectivityService(  874): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  874): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  874): calling update connectivity
D/ConnectivityService(  874): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  874):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  874):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  874):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  874): currentScore = 0, newScore = 60
D/ConnectivityService(  874):    accepting network in place of null
D/ConnectivityService(  874): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): Validated
,D/TelephonyNetworkFactory( 1474): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  874): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  874): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  874): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/AlarmManager(  874): waitForAlarm result :4
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7803): MountEmulatedStorage()
E/Zygote  ( 7803): v2
I/libpersona( 7803): KNOX_SDCARD checking this for 10078
I/libpersona( 7803): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7803 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,D/ConnectivityService(  874): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  874): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  874): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  874): getSBEnabled() enabled =false
D/SmartBondingService(  874): getSBEnabled() enabled =false
D/ConnectivityService(  874): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  874): getSBEnabled() enabled =false
,D/ConnectivityService(  874): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  874): calling update connectivity
,D/EntConnectivity(  874): Not allowed due to - mEnabled false
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,V/NetworkStats(  874): updateIfacesLocked()
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
V/NetworkStats(  874): performPollLocked(flags=0x1)
,D/ConnectivityService(  874): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkStatsFactory(  874): UpdateStatsForKnox
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  874): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  874):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  874):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  874): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  874): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  874): calling update connectivity
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  874): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  874): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,V/NetworkStats(  874): performPollLocked() took 4ms
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
,I/art     (  309): Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 14.318ms
,I/SELinux ( 7803): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524290
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 262us total 8.169ms
,I/SELinux ( 7803): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524290
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SELinux ( 7803): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/NtpTrustedTime(  874): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
,D/SmartBondingService(  874): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  874): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/NtpTrustedTime(  874): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/NtpTrustedTime(  874): currentTimeMillis() cache hit
V/NetworkStats(  874): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 269us total 8.961ms
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  874): waitForAlarm result :4
,D/RCPManagerService(  874): exchangeData() failure , invalid userId
,D/RCPManagerService(  874): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 7803): TimaSignature is unavailable
D/ActivityThread( 7803): Added TimaKeyStore provider
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7434): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7434): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7434): StateMachine : Current State = 1
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7803): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/SecurityLogAgent( 7434): StateMachine : Changed Current State = 1
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/ActivityManager(  874): Killing 6856:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/BadgeProvider( 7803): onCreate
D/BadgeProvider( 7803): DatabaseHelper
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,D/BadgeProvider( 7803): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,D/com.peel.receiver.ConnectivityActionReceiver( 1726): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 1726): 
D/com.peel.receiver.ConnectivityActionReceiver( 1726): 
D/com.peel.receiver.ConnectivityActionReceiver( 1726): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1726): 
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 1726): 
D/com.peel.receiver.ConnectivityActionReceiver( 1726): 
D/com.peel.receiver.ConnectivityActionReceiver( 1726):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1726): 
,D/com.peel.receiver.ConnectivityActionReceiver( 1726): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1726): 
D/com.peel.receiver.ConnectivityActionReceiver( 1726): 
D/com.peel.receiver.ConnectivityActionReceiver( 1726): last run: 1453807483777 -- System.currentTimeMillis()-last_run: 23474469
,D/com.peel.receiver.ConnectivityActionReceiver( 1726): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1726): ... skip last_72_check
V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,D/BadgeProvider( 7803): sendNotify entered. [uri] : content://com.sec.badge/apps/1
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 7803): sendNotify, [notify] : null
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 7803): update, [uri] : content://com.sec.badge/apps/1
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 7803): update, [BadgeCount] : badgecount=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 7803): update, [UpdateCount] : 1
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
D/Launcher.Model( 1499): reloadBadges entered.
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,E/Zygote  ( 7819): MountEmulatedStorage()
E/Zygote  ( 7819): v2
I/libpersona( 7819): KNOX_SDCARD checking this for 10178
I/libpersona( 7819): KNOX_SDCARD not a persona
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,I/ActivityManager(  874): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7819 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,I/art     (  874): Explicit concurrent mark sweep GC freed 72149(3MB) AllocSpace objects, 15(565KB) LOS objects, 30% free, 36MB/52MB, paused 3.350ms total 122.216ms
,I/SELinux ( 7819): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7819): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7819): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  874): failed to open /acct/uid_10098/pid_6856/cgroup.procs: No such file or directory
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7758): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/TimaKeyStoreProvider( 7819): TimaSignature is unavailable
,D/ActivityThread( 7819): Added TimaKeyStore provider
,D/ResourcesManager( 7819): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  874): Killing 6907:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2475): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2475): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  874): failed to open /acct/uid_10033/pid_6907/cgroup.procs: No such file or directory
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7106): notifyNetworkActivated
,W/ActivityManager(  874): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 7106): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  874): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
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
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,D/hcjo    ( 7106): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7106): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7106): exit::IDLE
D/InitializeManagerStateMachine( 7106): entry::NETWORK_CHECK
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7106): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7106): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7106): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7106): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7106): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7106): entry::SUCCESS
D/hcjo    ( 7106): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7106): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7106): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7106): exit::SUCCESS
D/InitializeManagerStateMachine( 7106): entry::IDLE
,D/ConnectivityService(  874): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/Hs20UtilService( 1300): Starting #8
,I/Hs20UtilService( 1300): Message received 5007
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  874): MasterInitialState.processMessage what=3
,D/SmartBondingService(  874): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  874): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  874): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  874): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  874): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  874): getSBEnabled() enabled =false
D/SmartBondingService(  874): getSBEnabled() enabled =false
D/SmartBondingService(  874): getSBEnabled() enabled =false
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  874): CLocinfo wifi true 
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  874): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2152): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2152): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/accuweather( 2244): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5376): type=WIFI subType= reason=null isConnected=true
,I/DBG_DM  ( 3812): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3812): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7130): [#DCM#] [DCM_Performance] onReceive completed in time  201 microsec. 
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/SystemBroadcastReceiver( 7130): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7130): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7130): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DatabaseRebuilderTask( 7130): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Hs20UtilService( 1300): Starting #9
,I/Hs20UtilService( 1300): Message received 5007
,I/FrameworkService( 7130): [#DCM#] onCreate FrameworkService 
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  874): mCursor = null
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FrameworkService( 7130): [#DCM#] onCreate FrameworkService end 
,I/DCMConfig( 7130): [#DCM#] getSuccessState = true
,I/FrameworkService( 7130): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
,I/IntentHandler( 7130): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,I/Hs20UtilService( 1300): Starting #10
,I/Hs20UtilService( 1300): Message received 5007
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemUtils( 7130): [#DCM#] LM: false,AM:640622592
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,I/DCMThreadPoolExecutor( 7130): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7130): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@1f04b8d5 is submitted
I/FrameworkService( 7130): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 22046 mirosec. 
,I/Hs20UtilService( 1300): Starting #11
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
I/Hs20UtilService( 1300): Message received 5007
,I/WifiStateMachine(  874): callSECApi what=220
D/WifiStateMachine(  874): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 6746): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6746): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6746): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6746): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PowerManagerService(  874): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=874
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/SMD     (  283): DCD ON
,I/DIAGMON_AGENT( 7523): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7523): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1170): value : false
,D/Finsky  ( 6541): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6541): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6541): [1] 5.onFinished: Scheduling replication attempt 2.
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/FOTA_Client( 7542): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7542): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7542): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7542): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7542): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7563): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7563): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453830958876
,I/KLMS-2.4.503: ( 7563): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7563): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7563): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7563): NetworkChangeOperations(): uploadRequestLog().START 
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7563): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7580): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5257): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6791): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6791): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6791): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6791): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6791): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6791): [SCU] == networkStateCheck == true
,I/SA      ( 6791): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6791): isChinaCountryCode : false
I/SA      ( 6791): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6791): [OR] == networkStateCheck true ==
,I/SA      ( 6791): [OR] GetMyCountryZoneTask
,I/SA      ( 6791): [OR] onReceive END
,I/SA      ( 6791): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6791): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6791): [SSP] query invoked
,I/SA      ( 6791): [TPMU] GetMccFromDB : null
,I/SA      ( 6791): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6791): [TPM] isNoProxy(default) : true
,D/accuweather( 7597): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7597): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7629): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7629): premStatus:2
,I/KnoxUsageLogPro( 7629): isEulaShown : false
I/KnoxUsageLogPro( 7629): KnoxUsageReceiver onReceive : not Processible, just return
,D/GCM     ( 1691): Connected
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/File    ( 6791): fail readDirectory() errno=2
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Headlines( 5520): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5520): getCountryCode(): countryCode = DE
,D/Headlines( 5520): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5520): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5520): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5520): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5520): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5520): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5520): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1691): Message class com.google.f.a.a.p
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7719): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7719): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7719): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  874): exchangeData() failure , invalid userId
,D/RCPManagerService(  874): exchangeData() failure , invalid userId
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7434): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7434): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7434): StateMachine : Current State = 1
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7434): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 1726): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 1726): 
D/com.peel.receiver.ConnectivityActionReceiver( 1726): 
D/com.peel.receiver.ConnectivityActionReceiver( 1726): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1726): 
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 1726): 
D/com.peel.receiver.ConnectivityActionReceiver( 1726): 
D/com.peel.receiver.ConnectivityActionReceiver( 1726):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1726): 
D/com.peel.receiver.ConnectivityActionReceiver( 1726): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1726): 
D/com.peel.receiver.ConnectivityActionReceiver( 1726): 
D/com.peel.receiver.ConnectivityActionReceiver( 1726): last run: 1453807483777 -- System.currentTimeMillis()-last_run: 23475287
D/com.peel.receiver.ConnectivityActionReceiver( 1726): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1726): ... skip last_72_check
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2475): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2475): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7106): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7106): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7106): exit::IDLE
D/InitializeManagerStateMachine( 7106): entry::NETWORK_CHECK
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7106): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7106): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7106): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7106): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7106): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7106): entry::SUCCESS
D/hcjo    ( 7106): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7106): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7106): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7106): exit::SUCCESS
D/InitializeManagerStateMachine( 7106): entry::IDLE
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
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
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,I/jxcore-log( 7340): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7340): 
,I/SA      ( 6791): [RC New] Execute method=[GET] start
,I/SA      ( 6791): [RC New] Security=[true]
,I/System.out( 6791): Thread-1105(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6791): Thread-1105(ApacheHTTPLog):isShipBuild true
,I/System.out( 6791): Thread-1105(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,V/AlarmManager(  874): waitForAlarm result :8
,I/jxcore-log( 7340): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7340): 
,I/jxcore-log( 7340): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7340): 
,I/jxcore-log( 7340): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7340): 
,I/jxcore-log( 7340): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7340): 
,I/jxcore-log( 7340): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7340): 
,I/jxcore-log( 7340): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7340): 
,I/jxcore-log( 7340): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7340): 
,I/SA      ( 6791): [RC New] [v2liruge] api execute + 671
I/SA      ( 6791): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6791): AsyncTask #1 calls detatch()
,I/SA      ( 6791): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6791): [OCP] update openData : PL
,I/SA      ( 6791): [TPMU] getNetworkMcc : 
,I/SA      ( 6791): [SCU] saveMccToPreferece Start
I/SA      ( 6791): [SCU] RegionMCC : 260
I/SA      ( 6791): [SSP] query invoked
,I/SA      ( 6791): [TPMU] GetMccFromDB : null
I/SA      ( 6791): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6791): [SCU] saveMccToPreferece End
I/SA      ( 6791): [RC New] executeRequest [v2liruge] end. 763
I/SA      ( 6791): [RC New] Execute end
I/SA      ( 6791): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6791): [OR] GetMyCountryZoneTask Success
,I/jxcore-log( 7340): Test app app.js loaded
I/jxcore-log( 7340): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7340): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7340): BLE advertisement is supported
I/jxcore-log( 7340): 
,I/chromium( 7340): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/dhcpcd  ( 7615): wlan0: sending IPv6 Router Solicitation
,I/WifiStateMachine(  874): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  874): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SMD     (  283): DCD ON
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  249): id=16 Removed Toast (8/9)
,I/SurfaceFlinger(  249): id=16 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PowerManagerService(  874): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 874) eventTime = 101082
,D/PowerManagerService(  874): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=874 (0x0)
,D/PowerManagerService(  874): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=874, ws=WorkSource{10059}) (elapsedTime=3496)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/GAV4    ( 7661): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6746): mConnectivityHandler : connected
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6746): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6746): ================================================
,I/CSTORAGE( 6746):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6746): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6746): [GetString-S]
E/art     ( 6746): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6746): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6746): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6746): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6746): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6746): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6746): [ensureRegistration] - No Samsung account
,E/SMD     (  283): DCD ON
,I/dhcpcd  ( 7615): wlan0: sending IPv6 Router Solicitation
,E/Watchdog(  874): !@Sync 3
,V/AlarmManager(  874): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  874): stay LED for fully charged
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  874): SIOP:: AP = 390, PST = 425, CUR = 300
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/PackageManager(  874): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  874): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,I/PowerManagerService(  874): [PWL] Off : 30s ago
,E/Zygote  ( 7892): MountEmulatedStorage()
E/Zygote  ( 7892): v2
I/libpersona( 7892): KNOX_SDCARD checking this for 10034
I/libpersona( 7892): KNOX_SDCARD not a persona
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,I/ActivityManager(  874): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7892 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/InputReader(  874): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/SELinux ( 7892): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7892): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7892): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/RegisteredServicesCache( 1455): empty dynamic service
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/TimaKeyStoreProvider( 7892): TimaSignature is unavailable
,D/ActivityThread( 7892): Added TimaKeyStore provider
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
,D/ResourcesManager( 7892): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/SecContentProvider2(  874): mCursor = null
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,I/FeatureConfig( 7892): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/BackupManagerService(  874): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  874): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  874): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 7892): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7892): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7892): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7892): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 7892): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7892): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7892): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7892): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7892): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7892): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7892): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7892): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 7892): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7892): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 7892): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7892): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7892): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7892): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7892): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7892): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7892): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7892): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7892): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7892): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7892): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7892): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7892): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7892): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7892): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7892): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7892): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7913): MountEmulatedStorage()
E/Zygote  ( 7913): v2
I/libpersona( 7913): KNOX_SDCARD checking this for 10035
I/libpersona( 7913): KNOX_SDCARD not a persona
,I/SELinux ( 7913): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7913): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7913): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  874): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=7913 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 6883:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7913): TimaSignature is unavailable
,D/ActivityThread( 7913): Added TimaKeyStore provider
,D/ResourcesManager( 7913): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/libprocessgroup(  874): failed to open /acct/uid_10099/pid_6883/cgroup.procs: No such file or directory
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7939): MountEmulatedStorage()
,E/Zygote  ( 7939): v2
I/libpersona( 7939): KNOX_SDCARD checking this for 10017
I/libpersona( 7939): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=7939 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/SELinux ( 7939): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7939): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7939): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7939): TimaSignature is unavailable
,D/ActivityThread( 7939): Added TimaKeyStore provider
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/BluetoothManager( 7913): getConnectedDevices
,D/-----SIC-----( 7913): ------------------skip uv
,D/-----SIC-----( 7913): ------------------skip SPO2
D/-----SIC-----( 7913): ------------------skip TGH
,I/SecureStorage( 7939): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  337): [INFO]: SPID(0x00000005)Credentials: uid 10017, gid 10017, pid 7939
I/SecureStorage(  337): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7913): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7913): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer( 7913): decode(32, 19359868, 4230)
,V/MediaPlayerService(  288): decode(30, 19359868, 4230)
,V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
,V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19359868, 4230)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
,V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  288): Audio channels(1)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  288): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
,V/MediaPlayerService(  288): wait for playback complete
I/AudioPlayer(  288): First fillBuffer call!!
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,V/MediaPlayer( 7913): decode(34, 19213040, 15440)
,V/MediaPlayerService(  288): decode(30, 19213040, 15440)
,V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
,V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19213040, 15440)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 1, 0, 0)
V/AudioCache(  288): prepared
,V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(2)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  288): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
V/MediaPlayerService(  288): wait for playback complete
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthServiceInstalled() : HealthService is Installed.
,I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
,V/AwesomePlayer(  288): onCheckAudioStatus
,V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 2, 0, 0)
,V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
,V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): addBatteryData
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  288): mAudioTrackVector clear
,D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,V/MediaPlayer( 7913): decode(36, 19257568, 9226)
V/MediaPlayerService(  288): decode(30, 19257568, 9226)
,V/MediaPlayerService(  288): player type = 3
,V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): setDefault
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
,V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
,V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
,V/StagefrightPlayer(  288): setDataSource(30, 19257568, 9226)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,I/ActivityManager(  874): Killing 6948:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
V/AudioCache(  288): notify(0xaf4131f0, 8, 0, 0)
V/AudioCache(  288): ignored
I/UpdateIcingCorporaServi( 1566): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/AdaptiveEventManager( 1170): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1170): M updateContainers()
D/AdaptiveEventContainerSmall( 1170): C updatePedoContainer()
,D/AdaptiveEventContainerSmall( 1170): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1170): pedoEvent == null
V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
,V/MediaPlayerService(  288): wait for prepare
,V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  288): Audio channels(2)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  288): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
,I/AudioPlayer(  288): First fillBuffer call!!
,E/Zygote  ( 7995): MountEmulatedStorage()
I/libpersona( 7995): KNOX_SDCARD checking this for 10075
E/Zygote  ( 7995): v2
I/libpersona( 7995): KNOX_SDCARD not a persona
I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
V/AwesomePlayer(  288): onCheckAudioStatus
,I/ActivityManager(  874): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7995 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/MediaPlayerService(  288): wait for playback complete
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x76, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
,V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
,V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
,V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,V/MediaPlayer( 7913): decode(37, 19364180, 4890)
,I/SELinux ( 7995): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  874): Killing 6954:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
D/AdaptiveEventManager( 1170): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1170): M updateContainers()
D/AdaptiveEventContainerSmall( 1170): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1170): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1170): pedoEvent == null
V/MediaPlayerService(  288): decode(30, 19364180, 4890)
V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
I/SELinux ( 7995): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7995): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19364180, 4890)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 1, 0, 0)
V/AudioCache(  288): prepared
,V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  288): Audio channels(1)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  288): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
V/MediaPlayerService(  288): wait for playback complete
,I/AudioPlayer(  288): First fillBuffer call!!
,I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
D/TimaKeyStoreProvider( 7995): TimaSignature is unavailable
,D/ActivityThread( 7995): Added TimaKeyStore provider
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
,V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x77, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/MediaPlayer( 7913): decode(38, 19290344, 17329)
V/MediaPlayerService(  288): decode(30, 19290344, 17329)
V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): setDefault
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
,V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19290344, 17329)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
,I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 200, 973, 0)
V/AudioCache(  288): ignored
,V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
,V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(2)
,I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
D/ResourcesManager( 7995): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
V/AudioCache(  288): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
,I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
V/MediaPlayerService(  288): wait for playback complete
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,E/DatabaseUtils(  874): Writing exception to parcel
E/DatabaseUtils(  874): java.lang.NullPointerException: key == null
E/DatabaseUtils(  874): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  874): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  874): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  874): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  874): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  874): 	at android.os.Binder.execTransact(Binder.java:446)
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
,V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/MediaPlayer( 7913): decode(39, 19190536, 6644)
V/MediaPlayerService(  288): decode(30, 19190536, 6644)
,V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
,V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19190536, 6644)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/UpdateIcingCorporaServi( 1566): UpdateCorporaTask done [took 121 ms] updated apps [took 120 ms] 
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(1)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  288): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
I/AudioPlayer(  288): First fillBuffer call!!
,I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,D/FileShare-Server( 7995): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,V/AudioCache(  288): notify(0xb05184c0, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
,V/AwesomePlayer(  288): onCheckAudioStatus
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,V/MediaPlayerService(  288): wait for playback complete
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  288): notify(0xb05184c0, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x79, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/MediaPlayer( 7913): decode(40, 19266876, 23389)
V/MediaPlayerService(  288): decode(30, 19266876, 23389)
,V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
I/libpersona( 8023): KNOX_SDCARD checking this for 1000
V/StagefrightPlayer(  288): setDataSource(30, 19266876, 23389)
I/libpersona( 8023): KNOX_SDCARD not a persona
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
E/Zygote  ( 8023): MountEmulatedStorage()
E/Zygote  ( 8023): v2
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/ActivityManager(  874): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8023 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 6977:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,I/SELinux ( 8023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  874): failed to open /acct/uid_10003/pid_6948/cgroup.procs: No such file or directory
,W/libprocessgroup(  874): failed to open /acct/uid_10020/pid_6954/cgroup.procs: No such file or directory
I/SELinux ( 8023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8023): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(2)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  288): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  288): notify(0xb03fd510, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
V/MediaPlayerService(  288): wait for playback complete
,I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,W/libprocessgroup(  874): failed to open /acct/uid_1000/pid_6977/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8023): TimaSignature is unavailable
,D/ActivityThread( 8023): Added TimaKeyStore provider
,D/ResourcesManager( 8023): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
,V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 8, 0, 0)
V/AudioCache(  288): ignored
,V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
,I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
,V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
,V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,V/MediaPlayer( 7913): decode(41, 19156232, 8154)
V/MediaPlayerService(  288): decode(30, 19156232, 8154)
,V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): setDefault
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19156232, 8154)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  288): notify(0xaf4131f0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
,V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 5, 0, 0)
,V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
,V/AwesomePlayer(  288): play
,V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,D/ShortcutReceiver( 8023):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(1)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
,I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  288): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 6, 0, 0)
,V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
I/AudioPlayer(  288): First fillBuffer call!!
V/MediaPlayerService(  288): wait for playback complete
,I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
,V/AwesomePlayer(  288): onCheckAudioStatus
,V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 2, 0, 0)
,V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 7, 0, 0)
V/AudioCache(  288): ignored
,V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
,V/AwesomePlayer(  288): addBatteryData
V/AwesomePlayer(  288): reset_l()
,V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
,D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x7b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
,I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
,V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
,V/AwesomePlayer(  288): mSecMediaClock clear
,V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,V/MediaPlayer( 7913): decode(42, 19129712, 4804)
V/MediaPlayerService(  288): decode(31, 19129712, 4804)
V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
,V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(31, 19129712, 4804)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(32) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
,V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(1)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  288): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
V/MediaPlayerService(  288): wait for playback complete
,I/AudioPlayer(  288): First fillBuffer call!!
,I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
D/PackageBroadcastService( 2475): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/MediaPlayer( 7913): decode(43, 19099164, 9400)
V/MediaPlayerService(  288): decode(30, 19099164, 9400)
,V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19099164, 9400)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,V/MediaPlayer( 7913): decode(49, 19172584, 4112)
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/MediaPlayerService(  288): decode(33, 19172584, 4112)
,I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(33, 19172584, 4112)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(36) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(1)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  288): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
V/MediaPlayerService(  288): wait for playback complete
,I/AudioPlayer(  288): First fillBuffer call!!
,I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthServiceInstalled() : HealthService is Installed.
,I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
,V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(1)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  288): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
,I/AudioPlayer(  288): First fillBuffer call!!
,I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
,E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  288): postAudioEOS delayUs (0)
V/AwesomePlayer(  288): onCheckAudioStatus
,V/MediaPlayerService(  288): wait for playback complete
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/PeopleContactsSync( 2475): CP2 sync disabled
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,V/MediaPlayer( 7913): decode(44, 19307764, 52024)
V/MediaPlayerService(  288): decode(30, 19307764, 52024)
,V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
,V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19307764, 52024)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
,V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(2)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  288): open(48000, 2, 0x0, 1, 0)
,V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,I/AudioPlayer(  288): First fillBuffer call!!
V/AudioCache(  288): notify(0xb03fd510, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
V/MediaPlayerService(  288): wait for playback complete
,I/ActivityManager(  874): Killing 7004:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
,V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 2, 0, 0)
,V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd510, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
,V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  288): notify(0xb03fd510, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
,I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
,V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
,V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
,V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,V/MediaPlayer( 7913): decode(45, 19172584, 4112)
V/MediaPlayerService(  288): decode(29, 19172584, 4112)
,W/libprocessgroup(  874): failed to open /acct/uid_10112/pid_7004/cgroup.procs: No such file or directory
V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(29, 19172584, 4112)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  288): notify(0xaf4131f0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(1)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  288): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 6, 0, 0)
,V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
V/MediaPlayerService(  288): wait for playback complete
I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  288): postAudioEOS delayUs (0)
V/AwesomePlayer(  288): onCheckAudioStatus
,V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 7, 0, 0)
V/AudioCache(  288): ignored
,V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): addBatteryData
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xaf4131f0, 8, 0, 0)
V/AudioCache(  288): ignored
,V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
,V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
,V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/MediaPlayer( 7913): decode(46, 19235660, 21825)
V/MediaPlayerService(  288): decode(30, 19235660, 21825)
V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): setDefault
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
,V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19235660, 21825)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
,V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
,I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 200, 973, 0)
,V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
,V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  288): Audio channels(2)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  288): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 6, 0, 0)
,V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
V/MediaPlayerService(  288): wait for playback complete
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
,V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 2, 0, 0)
,V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
,V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb29c77e0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
,I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
,V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/MediaPlayer( 7913): decode(47, 19134596, 21552)
V/MediaPlayerService(  288): decode(30, 19134596, 21552)
V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19134596, 21552)
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 5, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  288): Audio channels(2)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  288): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
V/MediaPlayerService(  288): wait for playback complete
,I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 4292761, value : -2137358184
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 4292761, value : -2137358184
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream,
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
,V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 2, 0, 0)
,V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb05184c0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
,I/OggExtractor(  288): ~OggExtractor --
I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
,V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
,V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/MediaPlayer( 7913): decode(48, 19228560, 7017)
V/MediaPlayerService(  288): decode(30, 19228560, 7017)
,V/MediaPlayerService(  288): player type = 3
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): constructor
V/AwesomePlayer(  288): setDefault
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): StagefrightPlayer
V/AwesomePlayer(  288): setListener
V/StagefrightPlayer(  288): initCheck
V/AwesomePlayer(  288): setAudioSink
V/StagefrightPlayer(  288): setDataSource(30, 19228560, 7017)
V/AwesomePlayer(  288): reset_l()
,V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 8, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
D/Utils   (  288): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  288): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  288): mBitrate = -1 bits/sec
I/OggExtractor(  288): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  288): current audio track index (0) is added to vector
V/AwesomePlayer(  288): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  288): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  288): prepare
V/AwesomePlayer(  288): prepareAsync
,V/MediaPlayerService(  288): wait for prepare
V/AwesomePlayer(  288): onPrepareAsyncEvent
I/SecMediaClock(  288): SecMediaClock constructor
I/SecMediaClock(  288): reset
I/SecVideoCapture(  288): SecVideoCapture constructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): initAudioDecoder
V/AwesomePlayer(  288): checkOffloadExceptions is true
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
,V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  288): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  288): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  288): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  288): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  288): finishAsyncPrepare_l
V/AwesomePlayer(  288): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 200, 973, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 5, 0, 0)
,V/AudioCache(  288): ignored
V/AwesomePlayer(  288): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 1, 0, 0)
V/AudioCache(  288): prepared
V/AudioCache(  288): wait - success
V/MediaPlayerService(  288): start
V/StagefrightPlayer(  288): start
V/AwesomePlayer(  288): play
V/AwesomePlayer(  288): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  288): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  288): start of Playback, useOffload 0
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  288): >>>UHQA initOutputFormat 16
I/OMXCodec(  288): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  288): Audio channels(2)
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  288): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  288): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  288): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 6, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): addBatteryData
V/MediaPlayerService(  288): wait for playback complete
I/AudioPlayer(  288): First fillBuffer call!!
I/AudioPlayer(  288): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  288): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/OMXCodec(  288): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  288): postAudioEOS delayUs (0)
,V/AwesomePlayer(  288): onCheckAudioStatus
V/AwesomePlayer(  288): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  288): onStreamDone
V/AwesomePlayer(  288): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  288): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 2, 0, 0)
V/AudioCache(  288): playback complete - thread will wake up later
V/AwesomePlayer(  288): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  288): notify(0xb03fd3d0, 7, 0, 0)
V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  288): addBatteryData
V/AudioCache(  288): wait - success
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  288): notify(0xb03fd3d0, 8, 0, 0)
,V/AudioCache(  288): ignored
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
D/AudioPlayer(  288): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  288): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  288): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  288): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  288): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  288): ~OggSource --
I/OggExtractor(  288): ~OggExtractor ++
I/OggExtractor(  288): ~MyVorbisExtractor ++ 
I/OggExtractor(  288): ~MyVorbisExtractor --
I/OggExtractor(  288): ~OggExtractor --
I/AudioPlayer(  288): reset out
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture(  288): SecVideoCapture destructor
I/SecVideoCapture(  288): reset
V/AwesomePlayer(  288): mSecCapture clear
I/SecMediaClock(  288): SecMediaClock destructor
V/AwesomePlayer(  288): mSecMediaClock clear
V/StagefrightPlayer(  288): ~StagefrightPlayer
V/StagefrightPlayer(  288): reset
V/AwesomePlayer(  288): reset_l()
,V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
V/AwesomePlayer(  288): destructor
V/AwesomePlayer(  288): reset_l()
V/AwesomePlayer(  288): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  288): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  288): mAudioTrackVector clear
V/AwesomePlayer(  288): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  288): mSecCapture clear
V/AwesomePlayer(  288): mSecMediaClock clear
,I/SecureStorage(  337): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  337): [INFO]: SPID(0x00000005)PID: 7939, TID: 7952
,I/SecureStorage( 7939): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 7939): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,I/SecSQLiteOpenHelper( 7913): getWritableDatabase(pwd)
,I/SecSQLiteOpenHelper( 7913): getDatabaseLocked(b,b,pwd)...
,I/SecSQLiteOpenHelper( 7913): Open platform.db in secure mode
,D/SecSQLiteDatabase( 7913): Android Version: 5.0
,D/SecSQLiteDatabase( 7913): Load library secsqlite.so for Android 5.0
,I/SecSQLiteDatabase( 7913): openSecureDatabase...
,I/SecSQLiteDatabase( 7913): private openSecureDatabase...
,I/SecSQLiteConnectionPool( 7913): OpenSecure
,I/SecSQLiteConnectionPool( 7913): OpenSecure with password
I/SecSQLiteConnectionPool( 7913): openSecureConnectionLocked
,I/SecSQLiteDatabase( 7913): ...private openSecureDatabase
,I/SecSQLiteDatabase( 7913): ...openSecureDatabase
,I/SecSQLiteOpenHelper( 7913): ...getDatabaseLocked(b,b,pwd)
,D/SecSQLiteOpenHelper( 7913): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7913): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/System.err( 7913): java.lang.NumberFormatException: Invalid int: "null"
,W/System.err( 7913): 	at java.lang.Integer.invalidInt(Integer.java:138)
,W/System.err( 7913): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 7913): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 7913): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:449)
W/System.err( 7913): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1173)
,W/System.err( 7913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7913): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7913): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SMD     (  283): DCD ON
,D/PreloadUpdateManagerStateMachine( 7106): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7106): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7106): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7106): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7106): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7106): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7106): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7106): entry::IDLE
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/dhcpcd  ( 7615): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7615): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine( 7106): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7106): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7106): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7106): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7106): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7106): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7106): entry::IDLE
,E/SMD     (  283): DCD ON
,I/GAV3    ( 7913): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager(  874): Waited long enough for: ServiceRecord{8637cb7 u0 com.samsung.dcm/.framework.FrameworkService}
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:m  (  874): SIOP:: AP = 360, PST = 419, CUR = 300
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/FactoryTest( 6682): Not factory mode
,D/FactoryTest( 6682): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6682): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6682): still no open session command from host, so toast
,W/ContextImpl( 6682): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6682): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6682): Timeline: Activity_launch_request id:com.android.settings time:117493
,E/PersonaManagerService(  874): inState():  stateMachine is null !!
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  874): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  874): mDVFSHelper.acquire()
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
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/AlarmManager(  874): waitForAlarm result :4
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/MTPRx   ( 6682): started activity for popup
,V/AlarmManager(  874): waitForAlarm result :4
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  874): stay LED for fully charged
,I/SQLiteSecureOpenHelper( 3574): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3574): getDatabaseLocked(b,b,pwd)...
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  874): Plugged
I/MotionRecognitionService(  874): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6682): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6682): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6682): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6682): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6682): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6682): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6682): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6682): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6682): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/InputMethodManagerService(  874): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  874): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@16003707 attribute=null, token = android.os.BinderProxy@2ad3d370
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 1
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6682): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6682): dev.kiessupport is : TRUE
,D/Activity( 6682): performCreate Call secproduct feature valuefalse
D/Activity( 6682): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ActivityManager(  874): post active user change for 0
D/KnoxTimeoutHandler(  874): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  874): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/Timeline( 7340): Timeline: Activity_idle id: android.os.BinderProxy@366ec65 time:117936
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6541): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6541): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6541): [1] 5.onFinished: Scheduling replication attempt 3.
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  283): DCD ON
,W/ActivityManager(  874): mDVFSHelper.release()
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:m  (  874): SIOP:: AP = 340, PST = 407, CUR = 300
,D/X       (  874): broadcastSiopLevelIntent:: currentSiopLevel = -1
,I/PowerManagerService(  874): [PWL] Off : 50s ago
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,D/ContentApp( 1222):  LEVEL : -1
,I/SystemBroadcastReceiver( 7130): [#DCM#] [DCM_Performance] onReceive completed in time  19494 microsec. 
,E/Zygote  ( 8130): MountEmulatedStorage()
,E/Zygote  ( 8130): v2
I/libpersona( 8130): KNOX_SDCARD checking this for 10054
,I/libpersona( 8130): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8130 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SystemBroadcastReceiver( 7130): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7130): [#DCM#] onReceive action = EVENT_SIOP
,I/SELinux ( 8130): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8130): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8130): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8130): TimaSignature is unavailable
,D/ActivityThread( 8130): Added TimaKeyStore provider
,D/ResourcesManager( 8130): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,E/SMD     (  283): DCD ON
,W/ResourcesManager( 8130): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8130): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8130): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8130): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8130): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 8130): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8130): core_num = 4
,W/linker  ( 8130): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8130): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/videowall-Global( 8130): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,D/videowall-Global( 8130): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8130):  SIOP_LEVEL: -1
,I/ActivityManager(  874): Killing 7020:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,W/libprocessgroup(  874): failed to open /acct/uid_10118/pid_7020/cgroup.procs: No such file or directory
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  283): DCD ON
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  283): DCD ON
,E/Watchdog(  874): !@Sync 4
,D/SSRM:m  (  874): SIOP:: AP = 320, PST = 391, CUR = 300
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,V/AlarmManager(  874): waitForAlarm result :4
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  874): stay LED for fully charged
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
I/MotionRecognitionService(  874): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     (  874): Explicit concurrent mark sweep GC freed 67493(3MB) AllocSpace objects, 16(386KB) LOS objects, 30% free, 37MB/53MB, paused 2.551ms total 228.123ms
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6541): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6541): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6541): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON,
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  874): SIOP:: AP = 320, PST = 375, CUR = 300
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  283): DCD ON
,V/AlarmManager(  874): waitForAlarm result :4
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6511): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6511): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6511): 	at kfv.a(PG:65)
E/HttpOperation( 6511): 	at kff.u(PG:385)
E/HttpOperation( 6511): 	at kfb.a(PG:29)
E/HttpOperation( 6511): 	at kff.l(PG:132)
E/HttpOperation( 6511): 	at dsf.a(PG:807)
E/HttpOperation( 6511): 	at fhk.a(PG:1126)
E/HttpOperation( 6511): 	at fhk.a(PG:908)
E/HttpOperation( 6511): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6511): 	at ihi.a(PG:22)
E/HttpOperation( 6511): 	at kft.a(PG:91)
E/HttpOperation( 6511): 	at kfv.a(PG:62)
E/HttpOperation( 6511): 	... 8 more
E/HttpOperation( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6511): 	at gde.c(Unknown Source)
E/HttpOperation( 6511): 	at gde.b(Unknown Source)
E/HttpOperation( 6511): 	at ihi.a(PG:19)
E/HttpOperation( 6511): 	... 10 more
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6511): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6511): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6511): 	at kfv.a(PG:65)
E/HttpOperation( 6511): 	at kff.u(PG:385)
E/HttpOperation( 6511): 	at kfb.a(PG:29)
E/HttpOperation( 6511): 	at kff.l(PG:132)
E/HttpOperation( 6511): 	at ieo.a(PG:43)
E/HttpOperation( 6511): 	at iep.a(PG:93)
E/HttpOperation( 6511): 	at fhn.a(PG:59)
E/HttpOperation( 6511): 	at lex.a(PG:85)
E/HttpOperation( 6511): 	at lex.b(PG:132)
E/HttpOperation( 6511): 	at fhk.a(PG:1146)
E/HttpOperation( 6511): 	at fhk.a(PG:908)
E/HttpOperation( 6511): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6511): 	at ihi.a(PG:22)
E/HttpOperation( 6511): 	at kft.a(PG:91)
E/HttpOperation( 6511): 	at kfv.a(PG:62)
E/HttpOperation( 6511): 	... 12 more
E/HttpOperation( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6511): 	at gde.c(Unknown Source)
E/HttpOperation( 6511): 	at gde.b(Unknown Source)
E/HttpOperation( 6511): 	at ihi.a(PG:19)
E/HttpOperation( 6511): 	... 14 more
,E/ExperimentLoader( 6511): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6511): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6511): 	at kfv.a(PG:65)
E/ExperimentLoader( 6511): 	at kff.u(PG:385)
E/ExperimentLoader( 6511): 	at kfb.a(PG:29)
E/ExperimentLoader( 6511): 	at kff.l(PG:132)
E/ExperimentLoader( 6511): 	at ieo.a(PG:43)
E/ExperimentLoader( 6511): 	at iep.a(PG:93)
E/ExperimentLoader( 6511): 	at fhn.a(PG:59)
E/ExperimentLoader( 6511): 	at lex.a(PG:85)
E/ExperimentLoader( 6511): 	at lex.b(PG:132)
E/ExperimentLoader( 6511): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6511): 	at fhk.a(PG:908)
E/ExperimentLoader( 6511): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6511): 	at ihi.a(PG:22)
E/ExperimentLoader( 6511): 	at kft.a(PG:91)
E/ExperimentLoader( 6511): 	at kfv.a(PG:62)
E/ExperimentLoader( 6511): 	... 12 more
E/ExperimentLoader( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6511): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6511): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6511): 	at ihi.a(PG:19)
E/ExperimentLoader( 6511): 	... 14 more
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  874): stay LED for fully charged
D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  874): Plugged
I/MotionRecognitionService(  874): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6511): [getaccountstatus] Unexpected exception
E/HttpOperation( 6511): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6511): 	at kfv.a(PG:65)
E/HttpOperation( 6511): 	at kff.u(PG:385)
E/HttpOperation( 6511): 	at kfb.a(PG:29)
E/HttpOperation( 6511): 	at ixd.a(PG:248)
E/HttpOperation( 6511): 	at ixd.b(PG:206)
E/HttpOperation( 6511): 	at ixd.a(PG:175)
E/HttpOperation( 6511): 	at fig.a(PG:78)
E/HttpOperation( 6511): 	at lex.a(PG:85)
E/HttpOperation( 6511): 	at lex.b(PG:132)
E/HttpOperation( 6511): 	at fhk.a(PG:1146)
E/HttpOperation( 6511): 	at fhk.a(PG:908)
E/HttpOperation( 6511): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6511): 	at ihi.a(PG:22)
E/HttpOperation( 6511): 	at kft.a(PG:91)
E/HttpOperation( 6511): 	at kfv.a(PG:62)
E/HttpOperation( 6511): 	... 12 more
E/HttpOperation( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6511): 	at gde.c(Unknown Source)
E/HttpOperation( 6511): 	at gde.b(Unknown Source)
E/HttpOperation( 6511): 	at ihi.a(PG:19)
E/HttpOperation( 6511): 	... 14 more
E/EsSyncAdapterService( 6511): Sync failure
E/EsSyncAdapterService( 6511): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6511): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6511): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6511): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6511): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6511): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6511): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6511): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6511): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6511): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6511): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6511): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6511): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6511): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6511): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6511): 	... 10 more
E/EsSyncAdapterService( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6511): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6511): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6511): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6511): 	... 12 more
E/EsSyncAdapterService( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6511): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6511): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6511): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6511): 	... 14 more
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  874): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 121279, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  874): mCursor = null
,E/SMD     (  283): DCD ON
,E/SQLiteLog( 1691): (10) POSIX Error : 11 SQLite Error : 3850
,I/PowerManagerService(  874): [PWL] Off : 75s ago
,E/SMD     (  283): DCD ON
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  874): SIOP:: AP = 310, PST = 361, CUR = 300
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,V/AlarmManager(  874): waitForAlarm result :4
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  874): stay LED for fully charged
D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
I/MotionRecognitionService(  874): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager(  874): waitForAlarm result :8
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1691): Explicit concurrent mark sweep GC freed 38523(2MB) AllocSpace objects, 28(2MB) LOS objects, 40% free, 17MB/29MB, paused 1.413ms total 74.804ms
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6541): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6541): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6541): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  283): DCD ON
,E/Watchdog(  874): !@Sync 5
,D/SSRM:m  (  874): SIOP:: AP = 310, PST = 351, CUR = 300
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  874): SIOP:: AP = 300, PST = 340, CUR = 300
,E/SMD     (  283): DCD ON
,V/AlarmManager(  874): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  874): stay LED for fully charged
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7273): Starting books sync, d
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1691): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1691): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1691): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1691): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1691): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7273): Authentication error
E/BooksAccountManager( 7273): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7273): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7273): null auth token
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,I/qtaguid ( 7273): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7273, getuid(): 10082
,I/qtaguid ( 7273): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7273, getuid(): 10082
,E/SMD     (  283): DCD ON
,I/qtaguid ( 7273): Untagging socket 34
,W/ApiaryClient( 7273): Error response from books API: {
W/ApiaryClient( 7273):  "error": {
W/ApiaryClient( 7273):   "errors": [
W/ApiaryClient( 7273):    {
W/ApiaryClient( 7273):     "domain": "global",
W/ApiaryClient( 7273):     "reason": "required",
W/ApiaryClient( 7273):     "message": "Login Required",
W/ApiaryClient( 7273):     "locationType": "header",
W/ApiaryClient( 7273):     "location": "Authorization"
W/ApiaryClient( 7273):    }
W/ApiaryClient( 7273):   ],
W/ApiaryClient( 7273):   "code": 401,
W/ApiaryClient( 7273):   "message": "Login Required"
W/ApiaryClient( 7273):  }
W/ApiaryClient( 7273): }
,W/ApiaryClient( 7273): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7273): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-279193381817519593&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7273): Headers suppressed
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  874): [PWL] Off : 105s ago
,I/PowerManagerService(  874): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  874): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  874): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=874, ws=WorkSource{10082}) (elapsedTime=1424)
,V/AlarmManager(  874): waitForAlarm result :4
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1691): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1691): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1691): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1691): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7273): Authentication error
E/BooksAccountManager( 7273): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7273): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpHelper( 7273): null auth token
,I/qtaguid ( 7273): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7273, getuid(): 10082
I/qtaguid ( 7273): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7273, getuid(): 10082
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 7273): Untagging socket 34
,W/ApiaryClient( 7273): Error response from books API: {
W/ApiaryClient( 7273):  "error": {
W/ApiaryClient( 7273):   "errors": [
W/ApiaryClient( 7273):    {
W/ApiaryClient( 7273):     "domain": "global",
W/ApiaryClient( 7273):     "reason": "required",
W/ApiaryClient( 7273):     "message": "Login Required",
W/ApiaryClient( 7273):     "locationType": "header",
W/ApiaryClient( 7273):     "location": "Authorization"
W/ApiaryClient( 7273):    }
W/ApiaryClient( 7273):   ],
W/ApiaryClient( 7273):   "code": 401,
W/ApiaryClient( 7273):   "message": "Login Required"
W/ApiaryClient( 7273):  }
W/ApiaryClient( 7273): }
,W/ApiaryClient( 7273): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7273): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-279193381817519593&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7273): Headers suppressed
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1691): Vacuum at: now=1453831041259 tag=VacuumService
,I/GoogleURLConnFactory( 1691): Using platform SSLCertificateSocketFactory
,W/Uploader( 1691): No account for auth token provided
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1691): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1691): (HTTPLog)-Static: isShipBuild true
I/System.out( 1691): (HTTPLog)-Thread-206-1015527229: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6541): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6541): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6541): [1] 5.onFinished: Giving up after 6 failures.
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1691): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1691): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1691): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1691): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7273): Authentication error
E/BooksAccountManager( 7273): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7273): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7273): null auth token
,I/qtaguid ( 7273): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7273, getuid(): 10082
,I/qtaguid ( 1691): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1691, getuid(): 10012
,I/qtaguid ( 7273): Untagging socket 34
,W/ApiaryClient( 7273): Error response from books API: {
W/ApiaryClient( 7273):  "error": {
W/ApiaryClient( 7273):   "errors": [
W/ApiaryClient( 7273):    {
W/ApiaryClient( 7273):     "domain": "global",
W/ApiaryClient( 7273):     "reason": "required",
W/ApiaryClient( 7273):     "message": "Login Required",
W/ApiaryClient( 7273):     "locationType": "header",
W/ApiaryClient( 7273):     "location": "Authorization"
W/ApiaryClient( 7273):    }
W/ApiaryClient( 7273):   ],
W/ApiaryClient( 7273):   "code": 401,
W/ApiaryClient( 7273):   "message": "Login Required"
W/ApiaryClient( 7273):  }
W/ApiaryClient( 7273): }
,W/ApiaryClient( 7273): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7273): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-279193381817519593&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7273): Headers suppressed
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 1691): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1691, getuid(): 10012
,E/SMD     (  283): DCD ON
,W/Uploader( 1691): No account for auth token provided
,I/qtaguid ( 1691): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1691, getuid(): 10012
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/Uploader( 1691): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1691): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1691): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1691): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1691): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1691): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1691): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1691): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1691): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1691): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1691): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1691): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1691): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/qtaguid ( 1691): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1691, getuid(): 10012
,W/Uploader( 1691): No account for auth token provided
,I/qtaguid ( 1691): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1691, getuid(): 10012
,W/Uploader( 1691): No account for auth token provided
,I/qtaguid ( 1691): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1691, getuid(): 10012
,E/BooksSync( 7273): Soft error
E/BooksSync( 7273): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7273): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-279193381817519593&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7273): Headers suppressed
E/BooksSync( 7273): 
E/BooksSync( 7273): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7273): Sync error
E/BooksSync( 7273): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7273): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-279193381817519593&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7273): Headers suppressed
E/BooksSync( 7273): 
E/BooksSync( 7273): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7273): Finished books sync
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  874): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 153826, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Uploader( 1691):  no longer exists, so no auth token.
,I/qtaguid ( 1691): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1691, getuid(): 10012
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  874): Explicit concurrent mark sweep GC freed 44623(2MB) AllocSpace objects, 21(791KB) LOS objects, 30% free, 36MB/52MB, paused 1.915ms total 116.205ms
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  874): mCursor = null
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1691): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 1691): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6511): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6511): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6511): 	at kfv.a(PG:65)
E/HttpOperation( 6511): 	at kff.u(PG:385)
E/HttpOperation( 6511): 	at kfb.a(PG:29)
E/HttpOperation( 6511): 	at kff.l(PG:132)
E/HttpOperation( 6511): 	at dsf.a(PG:807)
E/HttpOperation( 6511): 	at fhk.a(PG:1126)
E/HttpOperation( 6511): 	at fhk.a(PG:908)
E/HttpOperation( 6511): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6511): 	at ihi.a(PG:22)
E/HttpOperation( 6511): 	at kft.a(PG:91)
E/HttpOperation( 6511): 	at kfv.a(PG:62)
E/HttpOperation( 6511): 	... 8 more
E/HttpOperation( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6511): 	at gde.c(Unknown Source)
E/HttpOperation( 6511): 	at gde.b(Unknown Source)
E/HttpOperation( 6511): 	at ihi.a(PG:19)
E/HttpOperation( 6511): 	... 10 more
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,W/ProcessCpuTracker(  874): Skipping unknown process pid 8284
,W/ProcessCpuTracker(  874): Skipping unknown process pid 8287
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6511): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6511): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6511): 	at kfv.a(PG:65)
E/HttpOperation( 6511): 	at kff.u(PG:385)
E/HttpOperation( 6511): 	at kfb.a(PG:29)
E/HttpOperation( 6511): 	at kff.l(PG:132)
E/HttpOperation( 6511): 	at ieo.a(PG:43)
E/HttpOperation( 6511): 	at iep.a(PG:93)
E/HttpOperation( 6511): 	at fhn.a(PG:59)
E/HttpOperation( 6511): 	at lex.a(PG:85)
E/HttpOperation( 6511): 	at lex.b(PG:132)
E/HttpOperation( 6511): 	at fhk.a(PG:1146)
E/HttpOperation( 6511): 	at fhk.a(PG:908)
E/HttpOperation( 6511): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6511): 	at ihi.a(PG:22)
E/HttpOperation( 6511): 	at kft.a(PG:91)
E/HttpOperation( 6511): 	at kfv.a(PG:62)
E/HttpOperation( 6511): 	... 12 more
E/HttpOperation( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6511): 	at gde.c(Unknown Source)
E/HttpOperation( 6511): 	at gde.b(Unknown Source)
E/HttpOperation( 6511): 	at ihi.a(PG:19)
E/HttpOperation( 6511): 	... 14 more
,E/ExperimentLoader( 6511): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6511): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6511): 	at kfv.a(PG:65)
E/ExperimentLoader( 6511): 	at kff.u(PG:385)
E/ExperimentLoader( 6511): 	at kfb.a(PG:29)
E/ExperimentLoader( 6511): 	at kff.l(PG:132)
E/ExperimentLoader( 6511): 	at ieo.a(PG:43)
E/ExperimentLoader( 6511): 	at iep.a(PG:93)
E/ExperimentLoader( 6511): 	at fhn.a(PG:59)
E/ExperimentLoader( 6511): 	at lex.a(PG:85)
E/ExperimentLoader( 6511): 	at lex.b(PG:132)
E/ExperimentLoader( 6511): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6511): 	at fhk.a(PG:908)
E/ExperimentLoader( 6511): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6511): 	at ihi.a(PG:22)
E/ExperimentLoader( 6511): 	at kft.a(PG:91)
E/ExperimentLoader( 6511): 	at kfv.a(PG:62)
E/ExperimentLoader( 6511): 	... 12 more
E/ExperimentLoader( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6511): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6511): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6511): 	at ihi.a(PG:19)
E/ExperimentLoader( 6511): 	... 14 more
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,E/SQLiteLog( 1691): (10) POSIX Error : 11 SQLite Error : 3850
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6511): [getaccountstatus] Unexpected exception
E/HttpOperation( 6511): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6511): 	at kfv.a(PG:65)
E/HttpOperation( 6511): 	at kff.u(PG:385)
E/HttpOperation( 6511): 	at kfb.a(PG:29)
E/HttpOperation( 6511): 	at ixd.a(PG:248)
E/HttpOperation( 6511): 	at ixd.b(PG:206)
E/HttpOperation( 6511): 	at ixd.a(PG:175)
E/HttpOperation( 6511): 	at fig.a(PG:78)
E/HttpOperation( 6511): 	at lex.a(PG:85)
E/HttpOperation( 6511): 	at lex.b(PG:132)
E/HttpOperation( 6511): 	at fhk.a(PG:1146)
E/HttpOperation( 6511): 	at fhk.a(PG:908)
E/HttpOperation( 6511): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6511): 	at ihi.a(PG:22)
E/HttpOperation( 6511): 	at kft.a(PG:91)
E/HttpOperation( 6511): 	at kfv.a(PG:62)
E/HttpOperation( 6511): 	... 12 more
E/HttpOperation( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6511): 	at gde.c(Unknown Source)
E/HttpOperation( 6511): 	at gde.b(Unknown Source)
E/HttpOperation( 6511): 	at ihi.a(PG:19)
E/HttpOperation( 6511): 	... 14 more
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/EsSyncAdapterService( 6511): Sync failure
E/EsSyncAdapterService( 6511): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6511): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6511): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6511): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6511): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6511): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6511): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6511): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6511): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6511): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6511): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6511): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6511): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6511): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6511): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6511): 	... 10 more
E/EsSyncAdapterService( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6511): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6511): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6511): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6511): 	... 12 more
E/EsSyncAdapterService( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6511): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6511): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6511): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6511): 	... 14 more
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  874): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 179179, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  874): mCursor = null
,E/SQLiteLog( 1691): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  874): SIOP:: AP = 310, PST = 334, CUR = 300
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/BatteryService(  874): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,E/SMD     (  283): DCD ON
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  283): DCD ON
,E/Watchdog(  874): !@Sync 6
,D/SSRM:m  (  874): SIOP:: AP = 300, PST = 326, CUR = 300
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON,
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  874): SIOP:: AP = 300, PST = 317, CUR = 300
,E/SMD     (  283): DCD ON
,V/AlarmManager(  874): waitForAlarm result :4
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  874): [PWL] Off : 140s ago
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  874): SIOP:: AP = 300, PST = 311, CUR = 300
,E/SMD     (  283): DCD ON
,V/AlarmManager(  874): waitForAlarm result :8
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/BatteryService(  874): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/Watchdog(  874): !@Sync 7
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:m  (  874): SIOP:: AP = 300, PST = 307, CUR = 300
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  283): DCD ON
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 304, CUR = 300
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 2
,V/AlarmManager(  874): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  874): stay LED for fully charged
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7273): Starting books sync, d
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1691): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1691): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1691): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1691): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7273): Authentication error
E/BooksAccountManager( 7273): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7273): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7273): null auth token
,I/qtaguid ( 7273): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7273, getuid(): 10082
,E/SMD     (  283): DCD ON
,I/qtaguid ( 7273): Untagging socket 34
,W/ApiaryClient( 7273): Error response from books API: {
W/ApiaryClient( 7273):  "error": {
W/ApiaryClient( 7273):   "errors": [
W/ApiaryClient( 7273):    {
W/ApiaryClient( 7273):     "domain": "global",
W/ApiaryClient( 7273):     "reason": "required",
W/ApiaryClient( 7273):     "message": "Login Required",
W/ApiaryClient( 7273):     "locationType": "header",
W/ApiaryClient( 7273):     "location": "Authorization"
W/ApiaryClient( 7273):    }
W/ApiaryClient( 7273):   ],
W/ApiaryClient( 7273):   "code": 401,
W/ApiaryClient( 7273):   "message": "Login Required"
W/ApiaryClient( 7273):  }
W/ApiaryClient( 7273): }
,W/ApiaryClient( 7273): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7273): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4750316919037727597&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7273): Headers suppressed
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1691): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1691): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1691): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1691): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7273): Authentication error
E/BooksAccountManager( 7273): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7273): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7273): null auth token
,I/qtaguid ( 7273): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7273, getuid(): 10082
,I/qtaguid ( 7273): Untagging socket 34
,W/ApiaryClient( 7273): Error response from books API: {
W/ApiaryClient( 7273):  "error": {
W/ApiaryClient( 7273):   "errors": [
W/ApiaryClient( 7273):    {
W/ApiaryClient( 7273):     "domain": "global",
W/ApiaryClient( 7273):     "reason": "required",
W/ApiaryClient( 7273):     "message": "Login Required",
W/ApiaryClient( 7273):     "locationType": "header",
W/ApiaryClient( 7273):     "location": "Authorization"
W/ApiaryClient( 7273):    }
W/ApiaryClient( 7273):   ],
W/ApiaryClient( 7273):   "code": 401,
W/ApiaryClient( 7273):   "message": "Login Required"
W/ApiaryClient( 7273):  }
W/ApiaryClient( 7273): }
,W/ApiaryClient( 7273): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7273): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4750316919037727597&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7273): Headers suppressed
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1691): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1691): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1691): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1691): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1691): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7273): Authentication error
E/BooksAccountManager( 7273): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7273): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7273): null auth token
,I/qtaguid ( 7273): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7273, getuid(): 10082
,I/qtaguid ( 7273): Untagging socket 34
,W/ApiaryClient( 7273): Error response from books API: {
W/ApiaryClient( 7273):  "error": {
W/ApiaryClient( 7273):   "errors": [
W/ApiaryClient( 7273):    {
W/ApiaryClient( 7273):     "domain": "global",
W/ApiaryClient( 7273):     "reason": "required",
W/ApiaryClient( 7273):     "message": "Login Required",
W/ApiaryClient( 7273):     "locationType": "header",
W/ApiaryClient( 7273):     "location": "Authorization"
W/ApiaryClient( 7273):    }
W/ApiaryClient( 7273):   ],
W/ApiaryClient( 7273):   "code": 401,
W/ApiaryClient( 7273):   "message": "Login Required"
W/ApiaryClient( 7273):  }
W/ApiaryClient( 7273): }
,W/ApiaryClient( 7273): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7273): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4750316919037727597&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7273): Headers suppressed
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  283): DCD ON
,E/BooksSync( 7273): Soft error
E/BooksSync( 7273): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7273): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4750316919037727597&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7273): Headers suppressed
E/BooksSync( 7273): 
E/BooksSync( 7273): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7273): Sync error
E/BooksSync( 7273): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7273): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4750316919037727597&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7273): Headers suppressed
E/BooksSync( 7273): 
E/BooksSync( 7273): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7273): Finished books sync
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  874): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 215070, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  874): mCursor = null
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  874): SIOP:: AP = 300, PST = 302, CUR = 300
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  283): DCD ON
,E/Watchdog(  874): !@Sync 8
,I/PowerManagerService(  874): [PWL] Off : 180s ago
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 300, CUR = 300
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 298, CUR = 300
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,V/AlarmManager(  874): waitForAlarm result :4
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  874): stay LED for fully charged
D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
I/MotionRecognitionService(  874): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  283): DCD ON
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6511): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6511): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6511): 	at kfv.a(PG:65)
E/HttpOperation( 6511): 	at kff.u(PG:385)
E/HttpOperation( 6511): 	at kfb.a(PG:29)
E/HttpOperation( 6511): 	at kff.l(PG:132)
E/HttpOperation( 6511): 	at dsf.a(PG:807)
E/HttpOperation( 6511): 	at fhk.a(PG:1126)
E/HttpOperation( 6511): 	at fhk.a(PG:908)
E/HttpOperation( 6511): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6511): 	at ihi.a(PG:22)
E/HttpOperation( 6511): 	at kft.a(PG:91)
E/HttpOperation( 6511): 	at kfv.a(PG:62)
E/HttpOperation( 6511): 	... 8 more
E/HttpOperation( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6511): 	at gde.c(Unknown Source)
E/HttpOperation( 6511): 	at gde.b(Unknown Source)
E/HttpOperation( 6511): 	at ihi.a(PG:19)
E/HttpOperation( 6511): 	... 10 more
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6511): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6511): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6511): 	at kfv.a(PG:65)
E/HttpOperation( 6511): 	at kff.u(PG:385)
E/HttpOperation( 6511): 	at kfb.a(PG:29)
E/HttpOperation( 6511): 	at kff.l(PG:132)
E/HttpOperation( 6511): 	at ieo.a(PG:43)
E/HttpOperation( 6511): 	at iep.a(PG:93)
E/HttpOperation( 6511): 	at fhn.a(PG:59)
E/HttpOperation( 6511): 	at lex.a(PG:85)
E/HttpOperation( 6511): 	at lex.b(PG:132)
E/HttpOperation( 6511): 	at fhk.a(PG:1146)
E/HttpOperation( 6511): 	at fhk.a(PG:908)
E/HttpOperation( 6511): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6511): 	at ihi.a(PG:22)
E/HttpOperation( 6511): 	at kft.a(PG:91)
E/HttpOperation( 6511): 	at kfv.a(PG:62)
E/HttpOperation( 6511): 	... 12 more
E/HttpOperation( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6511): 	at gde.c(Unknown Source)
E/HttpOperation( 6511): 	at gde.b(Unknown Source)
E/HttpOperation( 6511): 	at ihi.a(PG:19)
E/HttpOperation( 6511): 	... 14 more
I/PhoneStatusBar( 1170): Icon Only
E/ExperimentLoader( 6511): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6511): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6511): 	at kfv.a(PG:65)
E/ExperimentLoader( 6511): 	at kff.u(PG:385)
E/ExperimentLoader( 6511): 	at kfb.a(PG:29)
E/ExperimentLoader( 6511): 	at kff.l(PG:132)
E/ExperimentLoader( 6511): 	at ieo.a(PG:43)
E/ExperimentLoader( 6511): 	at iep.a(PG:93)
E/ExperimentLoader( 6511): 	at fhn.a(PG:59)
E/ExperimentLoader( 6511): 	at lex.a(PG:85)
E/ExperimentLoader( 6511): 	at lex.b(PG:132)
E/ExperimentLoader( 6511): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6511): 	at fhk.a(PG:908)
E/ExperimentLoader( 6511): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6511): 	at ihi.a(PG:22)
E/ExperimentLoader( 6511): 	at kft.a(PG:91)
E/ExperimentLoader( 6511): 	at kfv.a(PG:62)
E/ExperimentLoader( 6511): 	... 12 more
E/ExperimentLoader( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6511): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6511): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6511): 	at ihi.a(PG:19)
E/ExperimentLoader( 6511): 	... 14 more
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/art     ( 1691): Explicit concurrent mark sweep GC freed 63352(3MB) AllocSpace objects, 76(5MB) LOS objects, 39% free, 18MB/30MB, paused 926us total 116.506ms
,E/SQLiteLog( 1691): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1691): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1691): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1691): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1691): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1691): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1691): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6511): [getaccountstatus] Unexpected exception
E/HttpOperation( 6511): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6511): 	at kfv.a(PG:65)
E/HttpOperation( 6511): 	at kff.u(PG:385)
E/HttpOperation( 6511): 	at kfb.a(PG:29)
E/HttpOperation( 6511): 	at ixd.a(PG:248)
E/HttpOperation( 6511): 	at ixd.b(PG:206)
E/HttpOperation( 6511): 	at ixd.a(PG:175)
E/HttpOperation( 6511): 	at fig.a(PG:78)
E/HttpOperation( 6511): 	at lex.a(PG:85)
E/HttpOperation( 6511): 	at lex.b(PG:132)
E/HttpOperation( 6511): 	at fhk.a(PG:1146)
E/HttpOperation( 6511): 	at fhk.a(PG:908)
E/HttpOperation( 6511): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6511): 	at ihi.a(PG:22)
E/HttpOperation( 6511): 	at kft.a(PG:91)
E/HttpOperation( 6511): 	at kfv.a(PG:62)
E/HttpOperation( 6511): 	... 12 more
E/HttpOperation( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6511): 	at gde.c(Unknown Source)
E/HttpOperation( 6511): 	at gde.b(Unknown Source)
E/HttpOperation( 6511): 	at ihi.a(PG:19)
E/HttpOperation( 6511): 	... 14 more
,E/EsSyncAdapterService( 6511): Sync failure
E/EsSyncAdapterService( 6511): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6511): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6511): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6511): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6511): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6511): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6511): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6511): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6511): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6511): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6511): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6511): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6511): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6511): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6511): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6511): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6511): 	... 10 more
E/EsSyncAdapterService( 6511): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6511): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6511): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6511): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6511): 	... 12 more
E/EsSyncAdapterService( 6511): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6511): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6511): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6511): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6511): 	... 14 more
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  874): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 245131, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2853): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2853): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  874): mCursor = null
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SQLiteLog( 1691): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 297, CUR = 300
,E/SMD     (  283): DCD ON
,V/AlarmManager(  874): waitForAlarm result :8
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/BatteryService(  874): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,E/Watchdog(  874): !@Sync 9
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  283): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager(  874): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,E/SMD     (  283): DCD ON
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  874): stay LED for fully charged
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  874): [PWL] Off : 225s ago
,E/SMD     (  283): DCD ON
,E/SMD     (  283): DCD ON
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 293, CUR = 300
,E/SMD     (  283): DCD ON
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/BatteryService(  874): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  283): DCD ON
,D/TimaService(  874): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  874): TimaServiceHandler.handleMessage what =1
,D/TimaService(  874): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  874): initializing...
,I/TLC_TIMA_PKM_initialize(  874): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  874): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  874): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  874): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  874): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  874): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  874): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  874): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  874): App is not loaded in QSEE
,D/QSEECOMAPI: (  874): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication(  874): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  874): Trustlet response is completed
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  283): DCD ON
,E/Watchdog(  874): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  874): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  874): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  874): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  874): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  283): DCD ON
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  874): stay LED for fully charged
D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
I/MotionRecognitionService(  874): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3244): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3244): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7340): --= Surplus to requirements =--
I/jxcore-log( 7340): 
,I/jxcore-log( 7340): ****TEST TOOK:  ms ****
I/jxcore-log( 7340): 
I/jxcore-log( 7340): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7340): 
,D/AndroidRuntime( 8391): 
D/AndroidRuntime( 8391): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8391): CheckJNI is OFF
,D/AndroidRuntime( 8391): setted country_code = Germany
,D/AndroidRuntime( 8391): setted countryiso_code = DE
D/AndroidRuntime( 8391): setted sales_code = DBT
,D/AndroidRuntime( 8391): readGMSProperty: start
D/AndroidRuntime( 8391): readGMSProperty: already setted!!
D/AndroidRuntime( 8391): readGMSProperty: end
D/AndroidRuntime( 8391): addProductProperty: start
,E/SMD     (  283): DCD ON
,E/AffinityControl( 8391): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8391): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  874): START PACKAGE DELETE: observer{967741183}
D/PackageManager(  874): pkg{<packageName>}
D/PackageManager(  874): user{0}
D/PackageManager(  874): caller{2000}
D/PackageManager(  874): flags{3}
,D/PersonaManagerService(  874): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  874): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  874): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  874): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  874): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  874): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  874): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  874): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  874): getApplicationUninstallationEnabled
D/ApplicationPolicy(  874): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  874): !@killApplicatoin: 10200, uninstall pkg
,I/ActivityManager(  874): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
,I/ActivityManager(  874): Killing 7340:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
,I/ActivityManager(  874):   Force finishing activity ActivityRecord{948446b u0 com.test.thalitest/.MainActivity t18}
,W/ActivityManager(  874): mDVFSHelper.acquire()
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
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/DBG_DM  ( 3812): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
,I/DBG_DM  ( 3812): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 71
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/DBG_DM  ( 3812): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 3812): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3812): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 71
,I/WindowState(  874): WIN DEATH: Window{3f3d56e9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  874): Client connection lost with reason: 4
,I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/DBG_DM  ( 3812): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/DBG_DM  ( 3812): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3812): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/FocusedStackFrame(  874): Set to : 0
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,I/ActivityManager(  874): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 3812): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 71
,I/DBG_DM  ( 3812): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 3812): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3812): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3812): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 3812): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 4606): Explicit concurrent mark sweep GC freed 5023(278KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 523us total 28.958ms
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,E/SamsungIME( 1860): mOCRHelper is null
,W/GeofencerStateMachine( 2171): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  874): Reconfiguring input devices.  changes=0x00000010
,I/KLMS-2.4.503: ( 7563): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7563): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1453831181291
,I/KLMS-2.4.503: ( 7563): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7563): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,I/art     ( 1566): Explicit concurrent mark sweep GC freed 59774(3MB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/27MB, paused 583us total 62.318ms
,D/ResourcesManager(  874): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ActivityManager(  874): post active user change for 0
D/KnoxTimeoutHandler(  874): postActiveUserChange for user 0
,I/DBG_DM  ( 3812): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),2 flag=404, com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/StatusBarManagerService(  874): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SurfaceWidgetView( 1499): destroyHardwareResources():116565167
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,V/WindowOrientationListener(  874): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,V/WindowOrientationListener(  874): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  874): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  874): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  874): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/Launcher( 1499): onRestart, Launcher: 358964676
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/Launcher( 1499): onStart, Launcher: 358964676
D/Launcher.HomeView( 1499): onStart
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/Launcher.HomeView( 1499): onStop
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2244): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2244): [237392/6] SurfaceWidget drawing first frame
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  874): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/StatusBarManagerService(  874): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  874): mCursor = null
,I/SurfaceFlinger(  249): id=17 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/9)
,I/SurfaceFlinger(  249): id=17 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/Timeline( 3812): Timeline: Activity_idle id: android.os.BinderProxy@1b49109 time:320258
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/RegisteredServicesCache( 1455): empty dynamic service
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/RCPManagerService(  874): PackageReceiver onReceive()
I/HarmonyEASService(  874): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  874): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  874): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  874): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  874): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  874): uID is 10200
V/EnterpriseBillingPolicy(  874): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  874): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  874): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  874): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  874): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  874): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  874): getBillingProfileForVpnEngine - end - null
,D/KnoxTimeoutHandler(  874): handleActiveUserChange for user 0
,D/TaskPersister(  874): removeObsoleteFile: deleting file=18_task.xml
,D/TaskPersister(  874): removeObsoleteFile: deleting file=17_task.xml
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,I/art     (  874): Explicit concurrent mark sweep GC freed 71967(4MB) AllocSpace objects, 63(1593KB) LOS objects, 30% free, 37MB/53MB, paused 8.477ms total 291.730ms
,I/art     (  874): WaitForGcToComplete blocked for 168.584ms for cause Explicit
,D/PackageManager(  874): delete codoeFile: 
,D/PackageManager(  874): result of delete: 1{967741183}
,D/AndroidRuntime( 8391): Shutting down VM
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  874): Explicit concurrent mark sweep GC freed 8054(476KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 1.315ms total 81.241ms
I/art     (  874): WaitForGcToComplete blocked for 103.927ms for cause Explicit
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,D/InputMethodManagerService(  874): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/EnterpriseDeviceManagerService(  874): Package has changed for user 0
D/EnterpriseDeviceManagerService(  874): Admin package name: com.google.android.gms
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/Zygote  ( 8429): MountEmulatedStorage()
E/Zygote  ( 8429): v2
I/libpersona( 8429): KNOX_SDCARD checking this for 10104
I/libpersona( 8429): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8429 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
W/InputMethodManagerService(  874): Got RemoteException sending setActive(false) notification to pid 7340 uid 10200
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SELinux ( 8429): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8429): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/SELinux ( 8429): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager(  874): mDVFSHelper.release()
I/Timeline(  874): Timeline: Activity_windows_visible id: ActivityRecord{30e78dc3 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:320556
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/TimaKeyStoreProvider( 8429): TimaSignature is unavailable
,D/ActivityThread( 8429): Added TimaKeyStore provider
,D/ResourcesManager( 8429): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,I/art     (  874): Explicit concurrent mark sweep GC freed 3157(154KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 1.653ms total 86.211ms
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/elm:14451( 8429): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8429): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8429): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/elm:14451( 8429): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 7939): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 7939): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7939): onReceive() : package name is not s health. Return !!!
,D/elm:14451( 8429): ElmAgentService : onCreate()
,D/elm:14451( 8429): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8429): MainReceiver.listeningToPackageRemoved()
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14451( 8429): MDMBridge.getInstance()
D/elm:14451( 8429): MDMBridge.getAllLicenseInfoFromSDK()
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  874): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/elm:14451( 8429): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14451( 8429): ElmAgentService : onDestroy().
,I/PCWCLIENTTRACE_PushUtil( 6746): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6746): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6746): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6746): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8448): MountEmulatedStorage()
E/Zygote  ( 8448): v2
I/libpersona( 8448): KNOX_SDCARD checking this for 10038
I/libpersona( 8448): KNOX_SDCARD not a persona
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/ActivityManager(  874): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8448 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager(  874): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  874): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/SELinux ( 8448): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  874): Killing 7036:com.samsung.helphub/1000 (adj 15): bgCount ##41
,I/SELinux ( 8448): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8448): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/TimaKeyStoreProvider( 8448): TimaSignature is unavailable
,D/ActivityThread( 8448): Added TimaKeyStore provider
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 8448): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  874): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  874): onPackageRemoved : com.test.thalitest
,W/libprocessgroup(  874): failed to open /acct/uid_1000/pid_7036/cgroup.procs: No such file or directory
,E/SPPClientService( 8448): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8448): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 8448): PushLog.txt file is not deleted.
D/SPPClientService( 8448): PushLog.txt file is not deleted.
,D/SPPClientService( 8448): ============PushLog. stop!
,E/SQLiteDatabase( 8448): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 8448): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8448): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8448): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 8448): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 8448): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8448): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8448): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8448): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 8448): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 8448): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8448): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 8448): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8448): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8448): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8448): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8448): 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
E/SQLiteDatabase( 8448): 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
E/SQLiteDatabase( 8448): 	at com.sec.spp.push.notisvc.registration.l.b(Unknown Source)
E/SQLiteDatabase( 8448): 	at com.sec.spp.push.notisvc.registration.l.a(Unknown Source)
E/SQLiteDatabase( 8448): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase( 8448): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 8448): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2945)
E/SQLiteDatabase( 8448): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 8448): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1499)
E/SQLiteDatabase( 8448): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8448): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 8448): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/SQLiteDatabase( 8448): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8448): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8448): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 8448): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/LNoti   ( 8448): [b] open fail. SQLException occured
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8466): MountEmulatedStorage()
E/Zygote  ( 8466): v2
I/libpersona( 8466): KNOX_SDCARD checking this for 10042
I/libpersona( 8466): KNOX_SDCARD not a persona
I/ActivityManager(  874): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8466 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager(  874): Killing 7070:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,I/SELinux ( 8466): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8466): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8466): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  874): failed to open /acct/uid_10166/pid_7070/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8466): TimaSignature is unavailable
,D/ActivityThread( 8466): Added TimaKeyStore provider
,D/ResourcesManager( 8466): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 8466): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8466): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ContextImpl( 8466): Unable to create files subdir /data/data/com.samsung.android.sdk.samsunglink/cache
E/ActivityThread( 8466): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8466): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7429da62 in tid 8466 (sdk.samsunglink)
,E/audit_log( 2086): File locking failed. error= Bad file number
,F/libc    ( 8466): Failed while talking to debuggerd: Broken pipe
E/audit_log( 2086): File locking failed. error= Bad file number
,I/ActivityManager(  874): Process com.samsung.android.sdk.samsunglink (pid 8466)(adj 0) has died(141,536)
,I/Zygote  (  309): Process 8466 exited due to signal (7)
,I/EventHub(  874): Removing device '/dev/input/event4' due to inotify event
,I/SA      ( 6791): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6791): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10200 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,F/libc    ( 2853): Fatal signal 7 (SIGBUS), code 2, fault addr 0x782317a2 in tid 2853 (ndroid.contacts)
,F/libc    ( 2853): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2086): File locking failed. error= Bad file number
,I/EventHub(  874): Removing device '/dev/input/event5' due to inotify event
,I/ActivityManager(  874): Process com.android.contacts (pid 2853)(adj 0) has died(150,536)
,F/libc    ( 1790): Fatal signal 7 (SIGBUS), code 2, fault addr 0x77e0044c in tid 1790 (d.process.acore)
,F/libc    ( 1790): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7828ee10 in tid 1857 (ContactsProvide)
F/libc    ( 1790): Unable to open connection to debuggerd: Connection refused
F/libc    ( 1790): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2086): File locking failed. error= Bad file number
,E/audit_log( 2086): File locking failed. error= Bad file number
,I/Zygote  (  309): Process 2853 exited due to signal (7)
,I/ActivityManager(  874): Process android.process.acore (pid 1790)(adj 0) has died(156,537)
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/SharedPreferencesImpl( 5999): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml
,E/Zygote  ( 8485): MountEmulatedStorage()
E/Zygote  ( 8485): v2
I/libpersona( 8485): KNOX_SDCARD checking this for 10050
I/libpersona( 8485): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=8485 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 276us total 20.059ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.848ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 8.080ms
,I/Zygote  (  309): Process 1790 exited due to signal (7)
,I/SELinux ( 8485): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8485): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/EventHub(  874): Removing device '/dev/input/event6' due to inotify event
,E/SELinux ( 8485): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8485): TimaSignature is unavailable
,D/ActivityThread( 8485): Added TimaKeyStore provider
,D/ResourcesManager( 8485): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8485): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8485): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8485): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8485): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8485): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ContextImpl( 8485): Unable to create files subdir /data/data/com.android.mms/cache
E/ActivityThread( 8485): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8485): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7429da62 in tid 8485 (com.android.mms)
,F/libc    ( 8485): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2086): File locking failed. error= Bad file number
,I/EventHub(  874): Removing device '/dev/input/event7' due to inotify event
,I/ActivityManager(  874): Process com.android.mms (pid 8485)(adj 0) has died(155,537)
,I/TactileAssist(  874): enable value -1
,I/TactileAssist(  874): internal enable value -1
I/TactileAssist(  874): intensity value -1
I/TactileAssist(  874): saveAppList value true
,I/TactileAssist(  874): List of disabled apps :
,I/TactileAssist(  874): de.zalando.mobile
,E/SharedPreferencesImpl(  874): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8504): MountEmulatedStorage()
E/Zygote  ( 8504): v2
I/libpersona( 8504): KNOX_SDCARD checking this for 10058
I/libpersona( 8504): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=8504 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
,I/EventHub(  874): Removing device '/dev/input/event8' due to inotify event
,I/Zygote  (  309): Process 8485 exited due to signal (7)
,I/SELinux ( 8504): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/EventHub(  874): Removing device '/dev/input/event9' due to inotify event
,I/SELinux ( 8504): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8504): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8504): TimaSignature is unavailable
,D/ActivityThread( 8504): Added TimaKeyStore provider
,D/ResourcesManager( 8504): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager( 8504): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ContextImpl( 8504): Unable to create files subdir /data/data/com.sec.android.app.soundalive/cache
E/ActivityThread( 8504): Unable to setupGraphicsSupport due to missing cache directory
,I/EventHub(  874): Removing device '/dev/input/event10' due to inotify event
,I/ActivityManager(  874): Killing 6592:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,I/UpdateIcingCorporaServi( 1566): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/AndroidRuntime( 8504): Shutting down VM
,F/libc    ( 8504): Fatal signal 7 (SIGBUS), code 2, fault addr 0x74276af8 in tid 8504 (.app.soundalive)
,F/libc    ( 8504): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2086): File locking failed. error= Bad file number
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8521): MountEmulatedStorage()
E/Zygote  ( 8521): v2
I/libpersona( 8521): KNOX_SDCARD checking this for 10003
I/libpersona( 8521): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=8521 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/SELinux ( 8521): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/EventHub(  874): Removing device '/dev/input/event11' due to inotify event
,I/SELinux ( 8521): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8521): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  874): Process com.sec.android.app.soundalive (pid 8504)(adj 9) has died(160,537)
,D/TimaKeyStoreProvider( 8521): TimaSignature is unavailable
,D/ActivityThread( 8521): Added TimaKeyStore provider
,D/ResourcesManager( 8521): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,W/ContextImpl( 8521): Unable to create files subdir /data/data/com.samsung.android.intelligenceservice/cache
,E/ActivityThread( 8521): Unable to setupGraphicsSupport due to missing cache directory
,E/SQLiteLog( 1566): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 1566): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,F/libc    ( 1566): Fatal signal 7 (SIGBUS), code 2, fault addr 0x78d582f1 in tid 8520 (IntentService[U)
,F/libc    ( 1566): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2086): File locking failed. error= Bad file number
,F/libc    ( 8521): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7429da62 in tid 8521 (lligenceservice)
,F/libc    ( 8521): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2086): File locking failed. error= Bad file number
,I/Zygote  (  309): Process 8504 exited due to signal (7)
I/ActivityManager(  874): Process com.samsung.android.intelligenceservice (pid 8521)(adj 0) has died(168,537)
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8538): MountEmulatedStorage()
E/Zygote  ( 8538): v2
I/libpersona( 8538): KNOX_SDCARD checking this for 1000
I/libpersona( 8538): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=8538 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/Zygote  (  309): Process 8521 exited due to signal (7)
I/SELinux ( 8538): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8538): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/WifiService(  874): Client connection lost with reason: 4
,I/Zygote  (  309): Process 1566 exited due to signal (7)
,I/ActivityManager(  874): Process com.google.android.googlequicksearchbox:search (pid 1566)(adj 1) has died(178,537)
W/libprocessgroup(  874): failed to open /acct/uid_10012/pid_6592/cgroup.procs: No such file or directory
,F/libc    (  874): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa0d5d810 in tid 1717 (Binder_F)
F/libc    (  874): Unable to open connection to debuggerd: Connection refused
,E/SELinux ( 8538): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/audit_log( 2086): File locking failed. error= Bad file number
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0

```
