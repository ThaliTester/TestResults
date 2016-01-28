#### Test 573480789efee08_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 7311): (284) automatic index on view_volumes(volume_id)
V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
--------- beginning of system
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/HttpOperation( 6528): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6528): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6528): 	at kfv.a(PG:65)
E/HttpOperation( 6528): 	at kff.u(PG:385)
E/HttpOperation( 6528): 	at kfb.a(PG:29)
E/HttpOperation( 6528): 	at kff.l(PG:132)
E/HttpOperation( 6528): 	at ieo.a(PG:43)
E/HttpOperation( 6528): 	at iep.a(PG:93)
E/HttpOperation( 6528): 	at fhn.a(PG:59)
E/HttpOperation( 6528): 	at lex.a(PG:85)
E/HttpOperation( 6528): 	at lex.b(PG:132)
E/HttpOperation( 6528): 	at fhk.a(PG:1146)
E/HttpOperation( 6528): 	at fhk.a(PG:908)
E/HttpOperation( 6528): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6528): 	at ihi.a(PG:22)
E/HttpOperation( 6528): 	at kft.a(PG:91)
E/HttpOperation( 6528): 	at kfv.a(PG:62)
E/HttpOperation( 6528): 	... 12 more
E/HttpOperation( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6528): 	at gde.c(Unknown Source)
E/HttpOperation( 6528): 	at gde.b(Unknown Source)
E/HttpOperation( 6528): 	at ihi.a(PG:19)
E/HttpOperation( 6528): 	... 14 more
E/ExperimentLoader( 6528): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6528): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6528): 	at kfv.a(PG:65)
E/ExperimentLoader( 6528): 	at kff.u(PG:385)
E/ExperimentLoader( 6528): 	at kfb.a(PG:29)
E/ExperimentLoader( 6528): 	at kff.l(PG:132)
E/ExperimentLoader( 6528): 	at ieo.a(PG:43)
E/ExperimentLoader( 6528): 	at iep.a(PG:93)
E/ExperimentLoader( 6528): 	at fhn.a(PG:59)
E/ExperimentLoader( 6528): 	at lex.a(PG:85)
E/ExperimentLoader( 6528): 	at lex.b(PG:132)
E/ExperimentLoader( 6528): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6528): 	at fhk.a(PG:908)
E/ExperimentLoader( 6528): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6528): 	at ihi.a(PG:22)
E/ExperimentLoader( 6528): 	at kft.a(PG:91)
E/ExperimentLoader( 6528): 	at kfv.a(PG:62)
E/ExperimentLoader( 6528): 	... 12 more
E/ExperimentLoader( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6528): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6528): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6528): 	at ihi.a(PG:19)
E/ExperimentLoader( 6528): 	... 14 more
I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ResourcesManager( 1658): creating new AssetManager and set to /system/app/Books/Books.apk
V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/GLSActivity( 1658): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1658): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1658): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1658): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1658): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1658): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1658): 	at android.os.Binder.execTransact(Binder.java:446)
D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
E/BooksAccountManager( 7311): Authentication error
E/BooksAccountManager( 7311): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7311): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7311): null auth token
D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/HttpOperation( 6528): [getaccountstatus] Unexpected exception
E/HttpOperation( 6528): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6528): 	at kfv.a(PG:65)
E/HttpOperation( 6528): 	at kff.u(PG:385)
E/HttpOperation( 6528): 	at kfb.a(PG:29)
E/HttpOperation( 6528): 	at ixd.a(PG:248)
E/HttpOperation( 6528): 	at ixd.b(PG:206)
E/HttpOperation( 6528): 	at ixd.a(PG:175)
E/HttpOperation( 6528): 	at fig.a(PG:78)
E/HttpOperation( 6528): 	at lex.a(PG:85)
E/HttpOperation( 6528): 	at lex.b(PG:132)
E/HttpOperation( 6528): 	at fhk.a(PG:1146)
E/HttpOperation( 6528): 	at fhk.a(PG:908)
E/HttpOperation( 6528): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6528): 	at ihi.a(PG:22)
E/HttpOperation( 6528): 	at kft.a(PG:91)
E/HttpOperation( 6528): 	at kfv.a(PG:62)
E/HttpOperation( 6528): 	... 12 more
E/HttpOperation( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6528): 	at gde.c(Unknown Source)
E/HttpOperation( 6528): 	at gde.b(Unknown Source)
E/HttpOperation( 6528): 	at ihi.a(PG:19)
E/HttpOperation( 6528): 	... 14 more
E/EsSyncAdapterService( 6528): Sync failure
E/EsSyncAdapterService( 6528): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6528): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6528): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6528): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6528): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6528): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6528): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6528): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6528): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6528): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6528): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6528): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6528): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6528): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6528): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6528): 	... 10 more
E/EsSyncAdapterService( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6528): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6528): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6528): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6528): 	... 12 more
E/EsSyncAdapterService( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6528): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6528): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6528): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6528): 	... 14 more
I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/System.out( 7311): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 7311): (HTTPLog)-Static: isShipBuild true
I/System.out( 7311): (HTTPLog)-Thread-1207-450204332: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
D/SyncManager(  891): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 62044, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SMD     (  284): DCD ON
I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
I/art     (  891): Explicit concurrent mark sweep GC freed 69989(3MB) AllocSpace objects, 16(516KB) LOS objects, 30% free, 36MB/52MB, paused 1.969ms total 117.977ms
D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  891): mCursor = null
I/qtaguid ( 7311): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7311, getuid(): 10082
D/AndroidRuntime( 7359): 
D/AndroidRuntime( 7359): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7359): CheckJNI is OFF
D/AndroidRuntime( 7359): setted country_code = Germany
D/AndroidRuntime( 7359): setted countryiso_code = DE
D/AndroidRuntime( 7359): setted sales_code = DBT
D/AndroidRuntime( 7359): readGMSProperty: start
D/AndroidRuntime( 7359): readGMSProperty: already setted!!
D/AndroidRuntime( 7359): readGMSProperty: end
D/AndroidRuntime( 7359): addProductProperty: start
D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
E/SQLiteLog( 1658): (10) POSIX Error : 11 SQLite Error : 3850
I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
E/AffinityControl( 7359): AffinityControl: registerfunction enter
D/AndroidRuntime( 7359): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  891): inState():  stateMachine is null !!
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  891): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  891): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  891): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 891  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  891): mDVFSHelper.acquire()
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIInstallConfirmActivity(415/onUserLeaveHint)] 
I/SQLiteSecureOpenHelper( 3558): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3558): getDatabaseLocked(b,b,pwd)...
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 75
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/AndroidRuntime( 7359): Shutting down VM
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onUserLeaveHint)] Home Key!!
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
D/LightsService(  891): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 891) 
D/LightsService(  891): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  891): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  891): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/PhoneStatusBar( 1168): Icon Only
D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WindowManager(  891): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
V/BitmapFactory( 1168): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
V/BitmapFactory( 1168): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
D/KnoxNotification( 1168): ----- inflateViews : modified publicViewLocal -----
E/Zygote  ( 7387): MountEmulatedStorage()
E/Zygote  ( 7387): v2
I/libpersona( 7387): KNOX_SDCARD checking this for 10200
I/libpersona( 7387): KNOX_SDCARD not a persona
I/ActivityManager(  891): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7387 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/KnoxNotification( 1168): ----- inflateViews : modified KnoxViewLocal -----
I/SELinux ( 7387): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/PhoneStatusBar( 1168): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@366b2d1d
D/PersonaManager( 1168): PersonaID is invalid or persona doesn't exists. : 0
D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1168): Icon Only
I/SELinux ( 7387): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7387): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
D/TimaKeyStoreProvider( 7387): TimaSignature is unavailable
D/ActivityThread( 7387): Added TimaKeyStore provider
V/ActivityManager(  891): Display changed displayId=0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/StatusBarManagerService(  891): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager( 7387): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/WebViewFactory( 7387): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7387): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/LibraryLoader( 7387): Loading: webviewchromium
I/LibraryLoader( 7387): Time to load native libraries: 2 ms (timestamps 9589-9591)
I/LibraryLoader( 7387): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
V/WebViewChromiumFactoryProvider( 7387): Binding Chromium to main looper Looper (main, tid 1) {2ae83866}
I/LibraryLoader( 7387): Expected native library version number "",actual native library version number ""
I/chromium( 7387): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7387): Initializing chromium process, renderers=0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
W/art     ( 7387): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1168): value : false
W/chromium( 7387): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7387): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7387): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/Adreno-EGL( 7387): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7387): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7387): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7387): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7387): Remote Branch: 
I/Adreno-EGL( 7387): Local Patches: 
I/Adreno-EGL( 7387): Reconstruct Branch: 
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/chromium( 7387): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/SSRM:m  (  891): SIOP:: AP = 360, PST = 428, CUR = 300
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/chromium( 7387): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/art     ( 7387): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7387): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/SystemWebViewEngine( 7387): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/art     ( 7387): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7387): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/Activity( 7387): performCreate Call secproduct feature valuefalse
D/Activity( 7387): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/OpenGLRenderer( 7387): Render dirty regions requested: true
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ActivityManager(  891): post active user change for 0
D/KnoxTimeoutHandler(  891): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  891): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/OpenGLRenderer( 7387): Initialized EGL, version 1.4
I/OpenGLRenderer( 7387): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7387): Enabling debug mode 0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/InputMethodManagerService(  891): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
E/Adreno-ES20( 7387): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7387): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
I/ActivityManager(  891): Displayed com.test.thalitest/.MainActivity: +718ms
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/Timeline( 7387): Timeline: Activity_idle id: android.os.BinderProxy@32ed2431 time:90089
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/JsMessageQueue( 7387): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/9)
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/CustomFrequencyManagerService(  891): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 891  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  891): mDVFSHelper.release()
I/Timeline(  891): Timeline: Activity_windows_visible id: ActivityRecord{9b3000b u0 com.test.thalitest/.MainActivity t18} time:90179
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/CustomFrequencyManagerService(  891): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 891  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/chromium( 7387): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7387): 
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (6/8)
,I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (-2/8)
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/jxcore_app_log( 7387): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361688832
,I/chromium( 7387): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/CustomFrequencyManagerService(  891): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 891  tag : ACTIVITY_RESUME_BOOSTER@10
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,E/SMD     (  284): DCD ON
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/jxcore-log( 7387): Initializing JXcore engine
,W/jxcore-log( 7387): JXcore engine is ready
,E/auditd  ( 2104): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  891): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  891): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7449): MountEmulatedStorage()
,E/Zygote  ( 7449): v2
I/libpersona( 7449): KNOX_SDCARD checking this for 1000
I/libpersona( 7449): KNOX_SDCARD not a persona
I/ActivityManager(  891): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7449 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/jxcore-log( 7387): Starting JXcore engine
,I/SELinux ( 7449): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7449): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7449): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7449): TimaSignature is unavailable
,D/ActivityThread( 7449): Added TimaKeyStore provider
,D/ResourcesManager( 7449): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7449):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7449):  SeDenialReceiver : File path = null
,I/ActivityManager(  891): Killing 5050:com.android.providers.calendar/u0a46 (adj 15): bgCount ##41
,W/jxcore-log( 7387): Platform android
W/jxcore-log( 7387): 
W/jxcore-log( 7387): Process ARCH arm
W/jxcore-log( 7387): 
,W/libprocessgroup(  891): failed to open /acct/uid_10046/pid_5050/cgroup.procs: No such file or directory
,I/qtaguid ( 7311): Untagging socket 34
,W/ApiaryClient( 7311): Error response from books API: {
W/ApiaryClient( 7311):  "error": {
W/ApiaryClient( 7311):   "errors": [
W/ApiaryClient( 7311):    {
W/ApiaryClient( 7311):     "domain": "global",
W/ApiaryClient( 7311):     "reason": "required",
W/ApiaryClient( 7311):     "message": "Login Required",
W/ApiaryClient( 7311):     "locationType": "header",
W/ApiaryClient( 7311):     "location": "Authorization"
W/ApiaryClient( 7311):    }
W/ApiaryClient( 7311):   ],
W/ApiaryClient( 7311):   "code": 401,
W/ApiaryClient( 7311):   "message": "Login Required"
W/ApiaryClient( 7311):  }
W/ApiaryClient( 7311): }
,W/ApiaryClient( 7311): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7311): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7428533648030124519&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7311): Headers suppressed
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 7387): JXcore Cordova bridge is ready!
I/jxcore-log( 7387): 
W/jxcore-log( 7387): JXcore engine is started
,D/TaskPersister(  891): removeObsoleteFile: deleting file=17_task_thumbnail.png
,I/jxcore-log( 7387): Toggling radios to true
I/jxcore-log( 7387): 
D/BluetoothAdapter( 7387): enable()
D/BluetoothAdapter( 7387): enable(): BT is already enabled..!
,D/WifiService(  891): New client listening to asynchronous messages
,I/WifiManager( 7387): packageName : com.test.thalitest
,D/SecContentProvider(  891): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  891): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  891): mCursor = null
,D/WifiService(  891): setWifiEnabled: true pid=7387, uid=10200
E/WifiService(  891): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  891): Permission Denial: getCurrentUser() from pid=7387, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  891): Failed getting userId using ActivityManagerNative
W/WifiService(  891): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7387, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  891): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  891): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  891): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  891): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  891): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  891): name = wifi_on
,I/WifiService(  891): disconnect: pid=7387, uid=10200
,I/wpa_supplicant( 1278): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7387): Radios toggled
I/jxcore-log( 7387): 
,I/jxcore-log( 7387): My device name is: samsung-SM-G900F
I/jxcore-log( 7387): 
,I/wpa_supplicant( 1278): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1278): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1278): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  891): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1278): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1278): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1278): Disconnected - do not scan
I/wpa_supplicant( 1278): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  891): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  891): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  891): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  891): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  891): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  891): InactiveState{ what=143375 }
,D/WifiP2pService(  891): P2pEnabledState{ what=143375 }
,V/AlarmManager(  891): waitForAlarm result :4
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  279): Clearing all IP addresses on wlan0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  891): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7481 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,E/Zygote  ( 7481): MountEmulatedStorage()
,E/Zygote  ( 7481): v2
I/libpersona( 7481): KNOX_SDCARD checking this for 10179
I/libpersona( 7481): KNOX_SDCARD not a persona
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,V/NativeCrypto( 1658): Read error: ssl=0x9bc7ce00: I/O error during system call, Connection timed out
,E/WifiStateMachine(  891): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  891): updateNetworkInfo()
,D/ConnectivityService(  891): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  891): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiConfigStore(  891): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller(  891): evaluateTrafficStatsPolling
,I/CLocInfoService(  891): External Intent Received android.net.wifi.STATE_CHANGE
,I/SELinux ( 7481): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7481): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/WifiStateMachine(  891): Start Disconnecting Watchdog 1
E/SELinux ( 7481): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1278): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1278): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1278): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1278): First Scan Start
,I/wpa_supplicant( 1278): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  891): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  891): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,V/NativeCrypto( 1658): SSL shutdown failed: ssl=0x9bc7ce00: I/O error during system call, Broken pipe
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,E/WifiStateMachine(  891): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4250, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/WifiP2pService(  891): InactiveState{ what=143375 }
,D/WifiP2pService(  891): P2pEnabledState{ what=143375 }
D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): DefaultState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): EvaluatingState{ when=-3ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Validated
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/CommandListener(  279): Clearing all IP addresses on wlan0
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
D/ConnectivityService(  891): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  891): calling update connectivity
,D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  891): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  891): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/EntConnectivity(  891): Not allowed due to - mEnabled false
E/WifiStateMachine(  891): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Disconnected - quitting
,I/WifiTrafficPoller(  891): evaluateTrafficStatsPolling
,D/WifiStateMachine(  891): updateConfiguredNetworkExpiration - currTime: 1453981573873
D/WifiStateMachine(  891): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524292
,E/WifiStateMachine(  891): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  891): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/ConnectivityService(  891): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  891): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/CLocInfoService(  891): External Intent Received android.net.wifi.STATE_CHANGE
D/CSLegacyTypeTracker(  891): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  891): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1456): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  891): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  891): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  891): NetworkAgent: NetworkAgent channel lost
,D/TimaKeyStoreProvider( 7481): TimaSignature is unavailable
,D/ActivityThread( 7481): Added TimaKeyStore provider
,D/ConnectivityService(  891): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  891): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  891): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  891): mCursor = null
,D/SmartBondingService(  891): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/ConnectivityService(  891): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/SmartBondingService(  891): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
V/NetworkStats(  891): updateIfacesLocked()
V/NetworkStats(  891): performPollLocked(flags=0x1)
E/ConnectivityService(  891): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/NetworkStatsFactory(  891): UpdateStatsForKnox
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  891): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1168): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1168): updateDataNetType()
,D/StatusBar.NetworkController( 1168): NoService, mRoamingIconId = 0
V/NetworkStats(  891): performPollLocked() took 6ms
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,V/NetworkStats(  891): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1168): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  891): mCursor = null
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,I/GAV2    ( 7311): Thread[GAThread,5,main]: No campaign data found.
,D/ResourcesManager( 7481): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,W/ResourcesManager( 7481): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/UMC:Core( 7481): onCreate(): 
,D/USER_AGENT( 7481): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
,D/[SAMSUNG SMARCART NATIVE]( 7481): initialize...
D/[SAMSUNG SMARCART NATIVE]( 7481): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/CSTORAGE( 7481): ================================================
I/CSTORAGE( 7481):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 7481): ================================================
I/TZ_CCM_C_GetFunctionList: ( 7481): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 7481): FINISHED: initialize rv:0
,D/UMC:SecurityUtils( 7481): Loaded server certificates: 0
,D/UMC:SecurityUtils( 7481): Loaded server certificates: 0
D/UMC:SecurityUtils( 7481): timaVersion on the device: 3.0
,D/UMC:CloudMDMSecurity( 7481): New Flow
,D/TimaService(  891): TIMA3: in ccmRegisterForDefaultCertificate
D/TimaService(  891): TIMA: in getTimaVersion
,I/        (  891): CCM JNI: In ccm_register_for_default_cert
I/        (  891): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  891): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  891): pInitArgs 0x9d6f7814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  891): &ctx = 0x9fbb6c1c
I/TLC_TZ_CCM: (  891): creating new ccm context...
,I/TLC_TZ_CCM: (  891): initializing ccm context...
I/TLC_TZ_CCM: (  891): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  891): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  891): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  891): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  891): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  891): process = tz_ccm, process_strlen = 6
,I/TZ: client_server_communication(  891): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  891): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  891): Client_Server_Open was called
I/TZ: client_server_communication(  891): IClientServer::IClientServer()
,I/TZ: client_server_communication(  891): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  891): IClientServer::~IClientServer()
,I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 1079): OPENSWCONN
I/TZ_CCM_SERVER( 1079): creating new ccm context...
I/TZ_CCM_SERVER( 1079): initializing ccm context...
,I/TZ_CCM_SERVER( 1079): root = /firmware/image, root_strlen = 15
I/TZ_CCM_SERVER( 1079): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1079): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1079): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1079): aligned max_sendmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1079): aligned max_recvmsg_size = 19456 = 0x4c00
,I/TZ: qc_tlc_communication( 1079): max_message_size = 38912 = 0x9800
D/QSEECOMAPI: ( 1079): QSEECom_get_handle sb_length = 0x9800
,D/QSEECOMAPI: ( 1079): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1079): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication( 1079): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
,I/TZ: client_server_communication(  891): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  891): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  891): ctx = 0x9118e760, comm = 0x6eafb088, sendmsg = 0x97009000, recvmsg = 0x9700dc00
I/TZ_init: (  891): TZ_init: sending initialization request...
,I/TZ: client_server_communication(  891): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  891): Calling Communicate()
I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1079): COMM
,I/TZ_init: (  891): TZ_init: successful initialization
,I/TLC_TZ_COMMON: key_db_init: (  891): Exercising TZ_DB_INIT in TLC
,I/TZ: client_server_communication(  891): Cmd id = 17, len = 19456
I/TZ: client_server_communication(  891): Calling Communicate()
,I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1079): COMM
,I/TZ_COMMON: tlc_key_db_util: (  891): DB Operation suceeded
,I/TLC_TZ_CCM: register for default cert: (  891): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  891): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  891): Calling Communicate()
I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1079): COMM
,I/TLC_TZ_CCM: register for default cert: (  891): TZ_CCM_register_default_TLC_END: DB file size to update is 0
,I/TLC_TZ_CCM: register for default cert: (  891): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  891): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
I/TZ: client_server_communication(  891): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  891): Calling Communicate()
I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(2) 16
,I/TZ_CCM_SERVER( 1079): COMM
,I/TZ: client_server_communication(  891): Client_Server_Close was called
I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1079): CLOSESWCONN
D/QSEECOMAPI: ( 1079): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1079): QSEECom_shutdown_app, app_id = 2
,I/TZ: client_server_communication(  891): Client_Server_Close succeeded
,D/UMC:CloudMDMSecurity( 7481): ccmRegisterForDefaultCertificate: 0
D/UMC:CloudMDMSecurity( 7481): TIMA service call for password change success!!
,D/UMC:AdminManager( 7481): init - start
,D/UMC:AdminManager( 7481): loadAdmins
,D/UMC:AdminManager( 7481): startPolicyHandlers
,I/UMC:TestPolicyHandler( 7481): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 7481): init - end
,V/UMC:AlarmHandler( 7481): Enter loadList
,D/GSLBManager( 7481): migrateStoredUrlFromOldPref
,D/GSLBManager( 7481): migrateStoredUrlFromOldPref : Migration Not Needed
,D/UMC:UMCAdmin( 7481): deactivateUMCAdminIfNotRequired : -1
,E/UMC:Utils( 7481): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 7481): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 7481): isContainer : 0
,V/AlarmManager(  891): waitForAlarm result :4
,W/LicenseLogService(  891): log() failed
,D/EnterpriseDeviceManagerService(  891): isManagedProfileUser(): userId = 0
,E/UMC:UMCAdmin( 7481): No active admin owned by uid 10179
,D/UMC:UMCAdmin( 7481): isContainer : 0
,D/UMC:UMCAdmin( 7481): deactivateUMCAdmin - UMC App Admin deactivated
,V/UMC:AlarmHandler( 7481): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
D/QuickStartReceiver( 7481): Msg Id : 2
,D/QuickStartReceiver( 7481): model : SM-G900F
D/QuickStartReceiver( 7481): id : 100
,I/ActivityManager(  891): Killing 6668:com.sec.android.app.videoplayer/u0a54 (adj 15): bgCount ##41
,I/Hs20UtilService( 1303): Starting #6
,I/Hs20UtilService( 1303): Message received 5007
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,I/Hs20UtilService( 1303): Starting #7
,I/Hs20UtilService( 1303): Message received 5007
D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,W/libprocessgroup(  891): failed to open /acct/uid_10054/pid_6668/cgroup.procs: No such file or directory
,D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  891): updateDataUsageMap
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  891): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  891): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  891): CLoinfo wifi false
D/SmartBondingService(  891): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/Tethering(  891): MasterInitialState.processMessage what=3
W/SLocation(  891): No Active Data Connection
D/accuweather( 2061): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  891): getNetworkEnabled : wifi : true mobile : true
,I/DBG_DM  ( 3810): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7148): [#DCM#] [DCM_Performance] onReceive completed in time  350 microsec. 
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3810): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/SystemBroadcastReceiver( 7148): [#DCM#] Calling notifyListeners. 
I/DCMController( 7148): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7148): [#DCM#] setIsConnectedForExtractors 
,I/NetworkMonitor( 5356): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 6765): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6765): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6765): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6765): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6765): noConnectivity : true
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7530): MountEmulatedStorage()
E/Zygote  ( 7530): v2
I/libpersona( 7530): KNOX_SDCARD checking this for 10002
I/libpersona( 7530): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7530 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  319): Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 267us total 13.232ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.354ms
,I/SELinux ( 7530): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7530): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7530): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 254us total 8.056ms
,D/TimaKeyStoreProvider( 7530): TimaSignature is unavailable
,D/ActivityThread( 7530): Added TimaKeyStore provider
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ResourcesManager( 7530): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1658): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1658): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1658): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1658): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1658): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1658): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1658): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7311): Authentication error
E/BooksAccountManager( 7311): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7311): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7311): null auth token
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,I/qtaguid ( 7311): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7311, getuid(): 10082
,I/qtaguid ( 7311): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7311, getuid(): 10082
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/ApiaryClient( 7311): errCount = 2: com.google.android.apps.books.net.HttpHelper$OfflineIoException: java.net.UnknownHostException: URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7428533648030124519&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7311): Headers suppressed
,E/BooksSync( 7311): Soft error
E/BooksSync( 7311): com.google.android.apps.books.net.HttpHelper$OfflineIoException: com.google.android.apps.books.net.HttpHelper$OfflineIoException: Device offline, skipping https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7428533648030124519&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7311): com.google.android.apps.books.net.HttpHelper.shouldSkipRetry(HttpHelper.java:88)
,E/BooksSync( 7311): Sync error
E/BooksSync( 7311): com.google.android.apps.books.net.HttpHelper$OfflineIoException: com.google.android.apps.books.net.HttpHelper$OfflineIoException: Device offline, skipping https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7428533648030124519&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7311): com.google.android.apps.books.net.HttpHelper.shouldSkipRetry(HttpHelper.java:88)
I/BooksSync( 7311): Finished books sync
,I/ActivityManager(  891): Killing 5892:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
D/SyncManager(  891): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 64657, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/Zygote  ( 7548): MountEmulatedStorage()
E/Zygote  ( 7548): v2
,I/libpersona( 7548): KNOX_SDCARD checking this for 1000
I/libpersona( 7548): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7548 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7548): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7548): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7548): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  891): Killing 6221:com.sec.providers.settingsearch/u0a168 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7548): TimaSignature is unavailable
,D/ActivityThread( 7548): Added TimaKeyStore provider
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  891): mCursor = null
,W/libprocessgroup(  891): failed to open /acct/uid_1000/pid_5892/cgroup.procs: No such file or directory
,D/ResourcesManager( 7548): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7548): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,W/libprocessgroup(  891): failed to open /acct/uid_10168/pid_6221/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7548): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7548): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7548): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7548): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7548): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/wpa_supplicant( 1278): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 1278): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1278): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1278): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  891): [1,453,981,574,912 ms] noteScanEnd no scan source
,E/WifiStateMachine(  891): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@f6bd577 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  891): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  891): setDetailed state send new extra info0x
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  891): mCursor = null
,I/CLocInfoService(  891): External Intent Received android.net.wifi.SCAN_RESULTS
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7564): MountEmulatedStorage()
,E/Zygote  ( 7564): v2
I/libpersona( 7564): KNOX_SDCARD checking this for 10011
I/libpersona( 7564): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7564 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7564): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7564): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7564): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7564): TimaSignature is unavailable
,D/ActivityThread( 7564): Added TimaKeyStore provider
,D/ResourcesManager( 7564): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 1278): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1278): Associated with C0.AA.48
E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  891): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  891): mCursor = null
,I/wpa_supplicant( 1278): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,V/AlarmManager(  891): waitForAlarm result :4
,E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  891): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  891): mCursor = null
,I/ActivityManager(  891): Killing 6725:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,I/FOTA_Client( 7564): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7564): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/wpa_supplicant( 1278): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1278): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1278): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1278): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1278): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1278): Blacklist: Clear (temp) 
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  891): Network connection established
,D/WifiNative-HAL(  891): callSECApiVoid - ID [50]
,E/WifiStateMachine(  891): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  891): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  891): External Intent Received android.net.wifi.STATE_CHANGE
,I/FOTA_Client( 7564): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7564): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/FOTA_Client( 7564): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,D/ConnectivityService(  891): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  891): Got NetworkAgent Messenger
D/ConnectivityService(  891): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  891): updateNetworkInfo()
D/ConnectivityService(  891): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  891): NetworkAgent connected
E/WifiStateMachine(  891): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  891): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  891): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  891): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  891): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  891): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  891): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  279): Setting iface cfg
,E/WifiStateMachine(  891): Start Dhcp Watchdog 2
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
W/libprocessgroup(  891): failed to open /acct/uid_10015/pid_6725/cgroup.procs: No such file or directory
D/SecContentProvider2(  891): mCursor = null
,E/Zygote  ( 7584): MountEmulatedStorage()
,E/Zygote  ( 7584): v2
I/libpersona( 7584): KNOX_SDCARD checking this for 10019
I/libpersona( 7584): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7584 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6745:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  891): calculateWifiScore() report new score 60
,I/WifiStateMachine(  891): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  891): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,D/ConnectivityService(  891): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  891): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  891): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  891): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/SELinux ( 7584): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7584): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7584): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7584): TimaSignature is unavailable
,D/ActivityThread( 7584): Added TimaKeyStore provider
,D/ResourcesManager( 7584): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,W/libprocessgroup(  891): failed to open /acct/uid_10016/pid_6745/cgroup.procs: No such file or directory
,I/KLMS-2.4.503: ( 7584): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7584): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453981575190
,I/KLMS-2.4.503: ( 7584): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7584): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7584): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  891): Killing 6431:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7603): MountEmulatedStorage()
E/Zygote  ( 7603): v2
I/libpersona( 7603): KNOX_SDCARD checking this for 10037
I/libpersona( 7603): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7603 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
E/WifiStateMachine(  891): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  891): do suspend false
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  891): mCursor = null
D/WifiP2pService(  891): InactiveState{ what=143375 }
D/WifiP2pService(  891): P2pEnabledState{ what=143375 }
,I/SELinux ( 7603): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7603): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7603): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7603): TimaSignature is unavailable
,D/ActivityThread( 7603): Added TimaKeyStore provider
,D/ResourcesManager( 7603): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,W/libprocessgroup(  891): failed to open /acct/uid_10034/pid_6431/cgroup.procs: No such file or directory
,I/SO_AGENT( 7603): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5217): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6800): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6800): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6800): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6800): [SLFUCHKMGR] constructor called
,I/SA      ( 6800): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6800): [OR] == isSIMCardReady false ==
,I/SA      ( 6800): [SCU] == networkStateCheck == false
I/SA      ( 6800): [OR] onReceive END
,E/SPPClientService( 5217): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7621): MountEmulatedStorage()
E/Zygote  ( 7621): v2
I/libpersona( 7621): KNOX_SDCARD checking this for 10071
I/libpersona( 7621): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7621 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,E/SMD     (  284): DCD ON
,I/SELinux ( 7621): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7621): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  891): Killing 4723:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,E/SELinux ( 7621): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7621): TimaSignature is unavailable
,D/ActivityThread( 7621): Added TimaKeyStore provider
,D/ResourcesManager( 7621): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7621): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7621): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7621): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/dhcpcd  ( 7636): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7636): version 5.5.6 starting
E/dhcpcd  ( 7636): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/comsamsunglog( 7621): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7621): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7621): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7621): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7621): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7621): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7621): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7621): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  891): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 10071
D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  891): ret = -1
,D/daemonapp( 1327): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7621): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,W/libprocessgroup(  891): failed to open /acct/uid_10035/pid_4723/cgroup.procs: No such file or directory
,D/accuweather( 7621): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7621): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7621): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
I/dhcpcd  ( 7636): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7636): wlan0: sendmsg: Cannot assign requested address
D/accuweather( 7621): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
I/dhcpcd  ( 7636): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7636): bssid match
D/accuweather( 7621): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,I/dhcpcd  ( 7636): wlan0: rebinding lease of 192.168.1.135
,D/daemonapp( 1327): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7621): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1327): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7621): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1327): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7621): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7621): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7646): MountEmulatedStorage()
E/Zygote  ( 7646): v2
I/libpersona( 7646): KNOX_SDCARD checking this for 1000
I/libpersona( 7646): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7646 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6054:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/SELinux ( 7646): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7646): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7646): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7646): TimaSignature is unavailable
,D/ActivityThread( 7646): Added TimaKeyStore provider
,D/ResourcesManager( 7646): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7646): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  891): failed to open /acct/uid_10042/pid_6054/cgroup.procs: No such file or directory
,I/KnoxUsageLogPro( 7646): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7646): premStatus:2
,I/KnoxUsageLogPro( 7646): isEulaShown : false
I/KnoxUsageLogPro( 7646): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7661): MountEmulatedStorage()
,E/Zygote  ( 7661): v2
I/libpersona( 7661): KNOX_SDCARD checking this for 10088
I/libpersona( 7661): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7661 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 5701:com.android.mms/u0a50 (adj 15): bgCount ##41
,I/SELinux ( 7661): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/CountryDetector(  891): No listener is left
,I/SELinux ( 7661): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7661): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7661): TimaSignature is unavailable
,D/ActivityThread( 7661): Added TimaKeyStore provider
,D/ResourcesManager( 7661): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  891): failed to open /acct/uid_10050/pid_5701/cgroup.procs: No such file or directory
,I/ActivityManager(  891): Killing 6824:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,D/Headlines( 5498): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5498): getCountryCode(): countryCode = DE
,D/Headlines( 5498): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5498): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5498): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
D/Headlines( 5498): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5498): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5498): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5498): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7677): MountEmulatedStorage()
E/Zygote  ( 7677): v2
I/libpersona( 7677): KNOX_SDCARD checking this for 10128
I/libpersona( 7677): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7677 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7677): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7677): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7677): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7677): TimaSignature is unavailable
,D/ActivityThread( 7677): Added TimaKeyStore provider
,D/ResourcesManager( 7677): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  891): failed to open /acct/uid_10051/pid_6824/cgroup.procs: No such file or directory
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7677): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7677): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7677): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7677): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7677): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7677): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7677): Loading: webviewchromium
,I/LibraryLoader( 7677): Time to load native libraries: 4 ms (timestamps 5267-5271)
,I/LibraryLoader( 7677): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7677): Binding Chromium to main looper Looper (main, tid 1) {1da0b514}
,I/LibraryLoader( 7677): Expected native library version number "",actual native library version number ""
,I/chromium( 7677): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7677): Initializing chromium process, renderers=0
,W/art     ( 7677): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7677): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7677): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7677): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7677): Requires BLUETOOTH permission
,I/Adreno-EGL( 7677): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7677): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7677): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7677): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7677): Remote Branch: 
I/Adreno-EGL( 7677): Local Patches: 
I/Adreno-EGL( 7677): Reconstruct Branch: 
,I/NSApplication( 7677): Starting up...
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7739): MountEmulatedStorage()
E/Zygote  ( 7739): v2
I/libpersona( 7739): KNOX_SDCARD checking this for 10138
I/libpersona( 7739): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7739 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6842:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/SELinux ( 7739): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7739): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7739): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7739): TimaSignature is unavailable
,D/ActivityThread( 7739): Added TimaKeyStore provider
,D/ResourcesManager( 7739): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7739): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7739): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7739): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup(  891): failed to open /acct/uid_10058/pid_6842/cgroup.procs: No such file or directory
,D/QuickConnect( 7739): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7739): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7739): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7754): MountEmulatedStorage()
,E/Zygote  ( 7754): v2
I/libpersona( 7754): KNOX_SDCARD checking this for 10163
I/libpersona( 7754): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7754 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6240:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SELinux ( 7754): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7754): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7754): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7754): TimaSignature is unavailable
,D/ActivityThread( 7754): Added TimaKeyStore provider
,D/ResourcesManager( 7754): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7754): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7754): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7754): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7754): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/dhcpcd  ( 7636): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,W/libprocessgroup(  891): failed to open /acct/uid_1000/pid_6240/cgroup.procs: No such file or directory
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,I/dhcpcd  ( 7636): wlan0: leased 192.168.1.135 for 86400 seconds
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,E/WifiStateMachine(  891): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,E/WifiStateMachine(  891): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/ConnectivityService(  891): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,E/Zygote  ( 7801): MountEmulatedStorage()
,E/Zygote  ( 7801): v2
,I/libpersona( 7801): KNOX_SDCARD checking this for 10078
I/libpersona( 7801): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7801 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,I/art     (  319): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 272us total 18.771ms
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 260us total 8.137ms
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 254us total 7.867ms
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,I/SELinux ( 7801): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,I/SELinux ( 7801): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7801): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
D/TimaKeyStoreProvider( 7801): TimaSignature is unavailable
,D/ActivityThread( 7801): Added TimaKeyStore provider
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,I/ActivityManager(  891): Killing 6864:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7449): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7449): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7449): StateMachine : Current State = 1
,D/SecurityLogAgent( 7449): StateMachine : Changed Current State = 1
,I/ActivityManager(  891): Killing 6921:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,E/WifiStateMachine(  891): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  891): InactiveState{ what=143375 }
,D/WifiP2pService(  891): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  891): WifiStateMachine DHCP successful
,E/WifiStateMachine(  891): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  891): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/com.peel.receiver.ConnectivityActionReceiver( 5602): ConnectivityActionReceiver onReceive
,E/WifiStateMachine(  891): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  891): Not connected state, yet.
E/WifiStateMachine(  891): VerifyingLinkState enter
D/ConnectivityService(  891): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/com.peel.receiver.ConnectivityActionReceiver( 5602): 
D/com.peel.receiver.ConnectivityActionReceiver( 5602): 
D/com.peel.receiver.ConnectivityActionReceiver( 5602): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5602): 
D/com.peel.receiver.ConnectivityActionReceiver( 5602): NO active network... no services...
D/com.peel.receiver.ConnectivityActionReceiver( 5602): 
D/com.peel.receiver.ConnectivityActionReceiver( 5602): 
D/com.peel.receiver.ConnectivityActionReceiver( 5602): last run: 1453981498710 -- System.currentTimeMillis()-last_run: 78133
D/com.peel.receiver.ConnectivityActionReceiver( 5602): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5602): ... skip last_72_check
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7754): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,W/libprocessgroup(  891): failed to open /acct/uid_10033/pid_6921/cgroup.procs: No such file or directory
,W/libprocessgroup(  891): failed to open /acct/uid_10098/pid_6864/cgroup.procs: No such file or directory
,I/art     (  891): Explicit concurrent mark sweep GC freed 58161(3MB) AllocSpace objects, 10(1505KB) LOS objects, 29% free, 37MB/53MB, paused 1.613ms total 122.384ms
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/WifiStateMachine(  891): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  891): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  891): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  891): callSECApiInt - ID [210]
,E/WifiStateMachine(  891): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  891): updateNetworkInfo()
,D/ConnectivityService(  891): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  891): Adding iface wlan0 to network 503
,E/Zygote  ( 7826): MountEmulatedStorage()
I/libpersona( 7826): KNOX_SDCARD checking this for 10178
E/Zygote  ( 7826): v2
I/libpersona( 7826): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7826 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CLocInfoService(  891): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  891): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  891): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  891): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  891): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  891): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  891): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  891): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  891): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  891): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  891): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  891): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  279): QcRouteController
,E/WifiStateMachine(  891): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  891): Now, connected state.
E/WifiStateMachine(  891): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  891): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  891): evaluateTrafficStatsPolling
,E/WifiStateMachine(  891): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/CLocInfoService(  891): External Intent Received android.net.wifi.STATE_CHANGE
I/WifiTrafficPoller(  891): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  891): mBoosterFLAG : 0
I/WifiTrafficPoller(  891): current booster mode : FullMode
,V/        (  279): QcRouteController
D/WifiNative-HAL(  891): callSECApiVoid - ID [212]
E/WifiStateMachine(  891): ConnectedState Enter  mScreenOn=true scanperiod=20000
I/CLocInfoService(  891): External Intent Received android.net.wifi.STATE_CHANGE
I/WifiStateMachine(  891): REQUEST_POWER_SAVE_ON
,V/        (  279): QcRouteController
,I/SELinux ( 7826): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7826): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7826): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ResourcesManager( 7801): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
V/        (  279): QcRouteController
D/BadgeProvider( 7801): onCreate
D/BadgeProvider( 7801): DatabaseHelper
V/        (  279): QcRouteController
V/        (  279): QcRouteController
D/TimaKeyStoreProvider( 7826): TimaSignature is unavailable
V/        (  279): QcRouteController
D/ActivityThread( 7826): Added TimaKeyStore provider
,D/BadgeProvider( 7801): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
D/Launcher.Model( 1462): reloadBadges entered.
D/BadgeProvider( 7801): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7801): sendNotify, [notify] : null
D/BadgeProvider( 7801): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7801): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7801): update, [UpdateCount] : 1
V/        (  279): QcRouteController
D/ResourcesManager( 7826): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
D/ConnectivityService(  891): Setting Dns servers for network 503 to [/192.168.1.1]
D/Nat464Xlat(  891): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  891): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  891): updateNetworkInfo()
D/ConnectivityService(  891): calling update connectivity
E/ConnectivityService(  891): updateNetworkInfo()
D/ConnectivityService(  891): ignoring duplicate network state non-change
D/ConnectivityService(  891): ignoring duplicate network state non-change
D/ConnectivityService(  891): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  891): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Connected
D/ConnectivityService(  891): calling update connectivity
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  891): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Validated
D/ConnectivityService(  891):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  891):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  891):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  891): currentScore = 0, newScore = 60
D/ConnectivityService(  891):    accepting network in place of null
D/ConnectivityService(  891): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1456): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker(  891): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  891): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  891): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  891): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  891): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  891): calling update connectivity
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  891): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/SmartBondingService(  891): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  891): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/ConnectivityService(  891): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  891): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  891):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  891):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  891): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  891): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  891): calling update connectivity
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkStats(  891): updateIfacesLocked()
V/NetworkStats(  891): performPollLocked(flags=0x1)
D/ConnectivityService(  891): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524290
D/SmartBondingService(  891): getNetworkEnabled : wifi : true mobile : true
D/NetworkStatsFactory(  891): UpdateStatsForKnox
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524290
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1168): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1168): updateDataNetType()
D/StatusBar.NetworkController( 1168): NoService, mRoamingIconId = 0
V/NetworkStats(  891): performPollLocked() took 8ms
D/StatusBar.NetworkController( 1168): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1168): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1168): updateDataNetType()
D/StatusBar.NetworkController( 1168): NoService, mRoamingIconId = 0
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
V/NetworkStats(  891): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1168): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
W/ActivityManager(  891): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/ActivityManager(  891): Killing 6887:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ChimeraCfgMgr( 2413): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2413): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  891): failed to open /acct/uid_10099/pid_6887/cgroup.procs: No such file or directory
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7127): notifyNetworkActivated
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2413): [AccountUtils] Account not ready
W/Kids    ( 2413): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2413): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2413): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2413): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2413): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2413): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2413): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2413): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2413): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2413): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2413): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2413): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/ContextImpl( 7127): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  891): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    ( 7127): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7127): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7127): exit::IDLE
D/InitializeManagerStateMachine( 7127): entry::NETWORK_CHECK
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7127): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7127): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7127): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7127): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7127): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7127): entry::SUCCESS
D/hcjo    ( 7127): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7127): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7127): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7127): exit::SUCCESS
D/InitializeManagerStateMachine( 7127): entry::IDLE
I/Hs20UtilService( 1303): Starting #8
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 1303): Message received 5007
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1303): Starting #9
,I/Hs20UtilService( 1303): Message received 5007
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1303): Starting #10
,I/Hs20UtilService( 1303): Message received 5007
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1303): Starting #11
,I/Hs20UtilService( 1303): Message received 5007
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  891): callSECApi what=220
D/WifiStateMachine(  891): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SurfaceFlinger(  249): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PowerManagerService(  891): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=891
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  891): MasterInitialState.processMessage what=3
,D/SmartBondingService(  891): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  891): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  891): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  891): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
I/CLocInfoService(  891): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  891): CLocinfo wifi true 
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  891): getNetworkEnabled : wifi : true mobile : true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2061): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2181): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/ContextImpl( 2181): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7148): [#DCM#] [DCM_Performance] onReceive completed in time  211 microsec. 
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/NetworkMonitor( 5356): type=WIFI subType= reason=null isConnected=true
,I/DBG_DM  ( 3810): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3810): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/SystemBroadcastReceiver( 7148): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7148): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7148): [#DCM#] setIsConnectedForExtractors 
,I/DatabaseRebuilderTask( 7148): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  891): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 6765): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6765): sales region : global
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PCWCLIENTTRACE_PushUtil( 6765): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6765): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FrameworkService( 7148): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7148): [#DCM#] onCreate FrameworkService end 
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/DCMConfig( 7148): [#DCM#] getSuccessState = true
I/FrameworkService( 7148): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
,I/IntentHandler( 7148): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
I/DIAGMON_AGENT( 7548): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7548): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SystemUtils( 7148): [#DCM#] LM: false,AM:653996032
,I/DCMThreadPoolExecutor( 7148): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7148): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@2bebe1c6 is submitted
I/FrameworkService( 7148): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 18337 mirosec. 
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/DatabaseRebuilderTask( 7148): [#DCM#] createLuceneReader done 
,I/DatabaseRebuilderTask( 7148): [#DCM#] resyncLocation   
I/DatabaseRebuilderTask( 7148): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
,I/DatabaseRebuilderTask( 7148): [#DCM#] topDocs hits = 0
,I/DatabaseRebuilderTask( 7148): [#DCM#] No of Location data to be added:  0
I/DatabaseRebuilderTask( 7148): [#DCM#] releaseLuceneReader done 
,I/DatabaseRebuilderTask( 7148): [#DCM#] Starting media manager do operation 
,I/SystemUtils( 7148): [#DCM#] setHeavySharedPref set as  false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/IntentHandler( 7148): [#DCM#] Stopping service with ids up to  1
,I/DCMThreadPoolExecutor( 7148): [#DCM#] afterExecute FutureTask
I/DCMController( 7148): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@2bebe1c6
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/FOTA_Client( 7564): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/FOTA_Client( 7564): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7564): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7564): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7564): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7584): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7584): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453981577772
,I/KLMS-2.4.503: ( 7584): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7584): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7584): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7584): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/KLMS-2.4.503: ( 7584): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/SO_AGENT( 7603): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5217): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6800): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6800): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6800): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6800): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6800): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6800): [SCU] == networkStateCheck == true
,I/SA      ( 6800): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6800): isChinaCountryCode : false
I/SA      ( 6800): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6800): [OR] == networkStateCheck true ==
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/SA      ( 6800): [OR] GetMyCountryZoneTask
,I/SA      ( 6800): [OR] onReceive END
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/SA      ( 6800): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 7621): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7621): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 6800): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/KnoxUsageLogPro( 7646): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7646): premStatus:2
,I/KnoxUsageLogPro( 7646): isEulaShown : false
I/KnoxUsageLogPro( 7646): KnoxUsageReceiver onReceive : not Processible, just return
,I/SA      ( 6800): [SSP] query invoked
,V/AlarmManager(  891): waitForAlarm result :4
,I/SA      ( 6800): [TPMU] GetMccFromDB : null
,I/SA      ( 6800): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6800): [TPM] isNoProxy(default) : true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/Headlines( 5498): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5498): getCountryCode(): countryCode = DE
,E/File    ( 6800): fail readDirectory() errno=2
,D/Headlines( 5498): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5498): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5498): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5498): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5498): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5498): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5498): requestUpdateNewsWelcomeCard !!! no welcome card
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7739): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7739): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7739): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7449): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7449): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7449): StateMachine : Current State = 1
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7449): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5602): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 5602): 
D/com.peel.receiver.ConnectivityActionReceiver( 5602): 
D/com.peel.receiver.ConnectivityActionReceiver( 5602): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5602): 
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 5602): 
D/com.peel.receiver.ConnectivityActionReceiver( 5602): 
D/com.peel.receiver.ConnectivityActionReceiver( 5602):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5602): 
D/com.peel.receiver.ConnectivityActionReceiver( 5602): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5602): 
D/com.peel.receiver.ConnectivityActionReceiver( 5602): 
D/com.peel.receiver.ConnectivityActionReceiver( 5602): last run: 1453981498710 -- System.currentTimeMillis()-last_run: 79266
D/com.peel.receiver.ConnectivityActionReceiver( 5602): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5602): ... skip last_72_check
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2413): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2413): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7127): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7127): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7127): exit::IDLE
D/InitializeManagerStateMachine( 7127): entry::NETWORK_CHECK
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7127): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7127): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7127): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7127): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7127): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7127): entry::SUCCESS
D/hcjo    ( 7127): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7127): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7127): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7127): exit::SUCCESS
D/InitializeManagerStateMachine( 7127): entry::IDLE
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  891): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Kids    ( 2413): [AccountUtils] Account not ready
W/Kids    ( 2413): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2413): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2413): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2413): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2413): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2413): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2413): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2413): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2413): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2413): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2413): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2413): 	at java.lang.Thread.run(Thread.java:818)
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1658): Explicit concurrent mark sweep GC freed 27953(1691KB) AllocSpace objects, 17(1377KB) LOS objects, 40% free, 17MB/29MB, paused 504us total 38.581ms
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6558): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6558): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6558): [1] 5.onFinished: Scheduling replication attempt 2.
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  284): DCD ON
,I/jxcore-log( 7387): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7387): 
,I/SA      ( 6800): [RC New] Execute method=[GET] start
,I/SA      ( 6800): [RC New] Security=[true]
,I/System.out( 6800): Thread-1105(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6800): Thread-1105(ApacheHTTPLog):isShipBuild true
,I/System.out( 6800): Thread-1105(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,W/ProcessCpuTracker(  891): Skipping unknown process pid 7892
,D/GCM     ( 1658): Connected
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1658): Message class com.google.f.a.a.p
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GCM     ( 2413): Message from null null
,E/GCM     ( 2413): Dropping message from null
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  891): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  891): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  891): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  891): identical MTU - not setting
,D/ConnectivityService(  891): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  891): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  279): QcRouteController
,E/WifiStateMachine(  891): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService(  891): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  891): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
,D/SmartBondingService(  891): getSBEnabled() enabled =false
,V/        (  279): QcRouteController
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
,D/ConnectivityService(  891): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  891): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  891): calling update connectivity
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524295
D/ConnectivityService(  891): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1168): CM callback handler got msg 524295
,I/jxcore-log( 7387): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7387): 
,I/jxcore-log( 7387): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7387): 
,I/jxcore-log( 7387): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7387): 
,I/jxcore-log( 7387): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7387): 
,I/jxcore-log( 7387): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7387): 
,I/jxcore-log( 7387): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7387): 
,I/jxcore-log( 7387): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7387): 
,I/dhcpcd  ( 7636): wlan0: sending IPv6 Router Solicitation
,D/PowerManagerService(  891): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1168 (0x0)
,I/SA      ( 6800): [RC New] [v2liruge] api execute + 1458
,I/SA      ( 6800): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 6800): AsyncTask #1 calls detatch()
,I/SA      ( 6800): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6800): [OCP] update openData : PL
,I/SA      ( 6800): [TPMU] getNetworkMcc : 
,I/SA      ( 6800): [SCU] saveMccToPreferece Start
,I/SA      ( 6800): [SCU] RegionMCC : 260
I/SA      ( 6800): [SSP] query invoked
,I/SA      ( 6800): [TPMU] GetMccFromDB : null
,I/SA      ( 6800): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6800): [SCU] saveMccToPreferece End
,I/SA      ( 6800): [RC New] executeRequest [v2liruge] end. 1511
,I/SA      ( 6800): [RC New] Execute end
,I/SA      ( 6800): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6800): [OR] GetMyCountryZoneTask Success
,I/WifiStateMachine(  891): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  891): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/SSRM:m  (  891): SIOP:: AP = 420, PST = 428, CUR = 300
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PowerManagerService(  891): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 891) eventTime = 100039
,D/PowerManagerService(  891): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=891 (0x0)
,D/PowerManagerService(  891): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=891, ws=WorkSource{10059}) (elapsedTime=3485)
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/GAV4    ( 7677): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,E/SMD     (  284): DCD ON
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SurfaceFlinger(  249): id=17 Removed Toast (8/8)
,I/SurfaceFlinger(  249): id=17 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6765): mConnectivityHandler : connected
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6765): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6765): ================================================
,I/CSTORAGE( 6765):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6765): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6765): [GetString-S]
E/art     ( 6765): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6765): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6765): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6765): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6765): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6765): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6765): [ensureRegistration] - No Samsung account
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,I/dhcpcd  ( 7636): wlan0: sending IPv6 Router Solicitation
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,I/jxcore-log( 7387): Test app app.js loaded
I/jxcore-log( 7387): 
,I/chromium( 7387): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7387): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7387): BLE advertisement is supported
I/jxcore-log( 7387): 
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,D/PackageManager(  891): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  891): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/Zygote  ( 7927): MountEmulatedStorage()
E/Zygote  ( 7927): v2
I/libpersona( 7927): KNOX_SDCARD checking this for 10034
I/libpersona( 7927): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7927 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/SELinux ( 7927): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/SELinux ( 7927): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7927): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/RegisteredServicesCache( 1450): empty dynamic service
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/SMD     (  284): DCD ON
,D/TimaKeyStoreProvider( 7927): TimaSignature is unavailable
,D/ActivityThread( 7927): Added TimaKeyStore provider
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  891): mCursor = null
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/FeatureConfig( 7927): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/BackupManagerService(  891): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  891): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  891): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  891): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,E/Watchdog(  891): !@Sync 3
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
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
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7957): MountEmulatedStorage()
,E/Zygote  ( 7957): v2
I/libpersona( 7957): KNOX_SDCARD checking this for 10035
I/libpersona( 7957): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=7957 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6965:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,I/SELinux ( 7957): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7957): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7957): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7957): TimaSignature is unavailable
,D/ActivityThread( 7957): Added TimaKeyStore provider
,D/ResourcesManager( 7957): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/libprocessgroup(  891): failed to open /acct/uid_10003/pid_6965/cgroup.procs: No such file or directory
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7981): MountEmulatedStorage()
E/Zygote  ( 7981): v2
,I/libpersona( 7981): KNOX_SDCARD checking this for 10017
I/libpersona( 7981): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=7981 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/SELinux ( 7981): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7981): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7981): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7981): TimaSignature is unavailable
,D/ActivityThread( 7981): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/ResourcesManager( 7981): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/BluetoothManager( 7957): getConnectedDevices
,D/-----SIC-----( 7957): ------------------skip uv
,D/-----SIC-----( 7957): ------------------skip SPO2
,D/-----SIC-----( 7957): ------------------skip TGH
,I/SecureStorage( 7981): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  349): [INFO]: SPID(0x00000005)Credentials: uid 10017, gid 10017, pid 7981
I/SecureStorage(  349): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7957): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7957): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer( 7957): decode(33, 19359868, 4230)
,V/MediaPlayerService(  291): decode(30, 19359868, 4230)
,V/MediaPlayerService(  291): player type = 3
,V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): constructor
,V/AwesomePlayer(  291): setDefault
,V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
,V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): StagefrightPlayer
,V/AwesomePlayer(  291): setListener
V/StagefrightPlayer(  291): initCheck
V/AwesomePlayer(  291): setAudioSink
V/StagefrightPlayer(  291): setDataSource(30, 19359868, 4230)
,V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 8, 0, 0)
,V/AudioCache(  291): ignored
,V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
,D/Utils   (  291): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  291): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  291): mBitrate = -1 bits/sec
I/OggExtractor(  291): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  291): current audio track index (0) is added to vector
V/AwesomePlayer(  291): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer(  291): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  291): prepare
V/AwesomePlayer(  291): prepareAsync
,V/MediaPlayerService(  291): wait for prepare
V/AwesomePlayer(  291): onPrepareAsyncEvent
I/SecMediaClock(  291): SecMediaClock constructor
I/SecMediaClock(  291): reset
I/SecVideoCapture(  291): SecVideoCapture constructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): initAudioDecoder
V/AwesomePlayer(  291): checkOffloadExceptions is true
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  291): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  291): finishAsyncPrepare_l
V/AwesomePlayer(  291): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 200, 973, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 5, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 1, 0, 0)
V/AudioCache(  291): prepared
V/AudioCache(  291): wait - success
V/MediaPlayerService(  291): start
V/StagefrightPlayer(  291): start
V/AwesomePlayer(  291): play
V/AwesomePlayer(  291): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  291): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  291): start of Playback, useOffload 0
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  291): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] End Of Stream
,I/AudioPlayer(  291): Audio channels(1)
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  291): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  291): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 6, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): addBatteryData
V/MediaPlayerService(  291): wait for playback complete
,I/AudioPlayer(  291): First fillBuffer call!!
,I/AudioPlayer(  291): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  291): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,V/AwesomePlayer(  291): postAudioEOS delayUs (0)
V/AwesomePlayer(  291): onCheckAudioStatus
V/AwesomePlayer(  291): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  291): onStreamDone
V/AwesomePlayer(  291): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  291): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 2, 0, 0)
V/AudioCache(  291): playback complete - thread will wake up later
V/AwesomePlayer(  291): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 7, 0, 0)
V/AudioCache(  291): ignored
,V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  291): addBatteryData
,V/AudioCache(  291): wait - success
V/StagefrightPlayer(  291): reset
,V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 8, 0, 0)
,V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
D/AudioPlayer(  291): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  291): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  291): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  291): ~OggSource --
I/OggExtractor(  291): ~OggExtractor ++
I/OggExtractor(  291): ~MyVorbisExtractor ++ 
I/OggExtractor(  291): ~MyVorbisExtractor --
I/OggExtractor(  291): ~OggExtractor --
,I/AudioPlayer(  291): reset out
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  291): SecVideoCapture destructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): mSecCapture clear
I/SecMediaClock(  291): SecMediaClock destructor
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): ~StagefrightPlayer
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/AwesomePlayer(  291): destructor
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/MediaPlayer( 7957): decode(34, 19213040, 15440)
,V/MediaPlayerService(  291): decode(30, 19213040, 15440)
,V/MediaPlayerService(  291): player type = 3
,V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): constructor
,V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): reset_l()
,V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
,V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
,V/StagefrightPlayer(  291): StagefrightPlayer
V/AwesomePlayer(  291): setListener
V/StagefrightPlayer(  291): initCheck
V/AwesomePlayer(  291): setAudioSink
,V/StagefrightPlayer(  291): setDataSource(30, 19213040, 15440)
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  291): notify(0xb09091f0, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
,V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
,D/Utils   (  291): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  291): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  291): mBitrate = -1 bits/sec
I/OggExtractor(  291): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer(  291): current audio track index (0) is added to vector
V/AwesomePlayer(  291): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  291): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService(  291): prepare
V/AwesomePlayer(  291): prepareAsync
V/MediaPlayerService(  291): wait for prepare
,V/AwesomePlayer(  291): onPrepareAsyncEvent
I/SecMediaClock(  291): SecMediaClock constructor
I/SecMediaClock(  291): reset
I/SecVideoCapture(  291): SecVideoCapture constructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): initAudioDecoder
V/AwesomePlayer(  291): checkOffloadExceptions is true
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  291): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  291): finishAsyncPrepare_l
,V/AwesomePlayer(  291): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 200, 973, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 5, 0, 0)
V/AudioCache(  291): ignored
,V/AwesomePlayer(  291): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 1, 0, 0)
V/AudioCache(  291): prepared
V/AudioCache(  291): wait - success
V/MediaPlayerService(  291): start
V/StagefrightPlayer(  291): start
V/AwesomePlayer(  291): play
V/AwesomePlayer(  291): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  291): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  291): start of Playback, useOffload 0
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  291): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  291): Audio channels(2)
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  291): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  291): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 6, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): addBatteryData
I/AudioPlayer(  291): First fillBuffer call!!
I/AudioPlayer(  291): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  291): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,V/MediaPlayerService(  291): wait for playback complete
,I/ActivityManager(  891): Killing 6977:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  291): postAudioEOS delayUs (0)
V/AwesomePlayer(  291): onCheckAudioStatus
V/AwesomePlayer(  291): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  291): onStreamDone
V/AwesomePlayer(  291): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  291): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 2, 0, 0)
V/AudioCache(  291): playback complete - thread will wake up later
V/AwesomePlayer(  291): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 7, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  291): addBatteryData
V/AudioCache(  291): wait - success
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
D/AudioPlayer(  291): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  291): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  291): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  291): ~OggSource --
I/OggExtractor(  291): ~OggExtractor ++
I/OggExtractor(  291): ~MyVorbisExtractor ++ 
I/OggExtractor(  291): ~MyVorbisExtractor --
I/OggExtractor(  291): ~OggExtractor --
D/AdaptiveEventManager( 1168): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1168): M updateContainers()
D/AdaptiveEventContainerSmall( 1168): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1168): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1168): pedoEvent == null
,I/AudioPlayer(  291): reset out
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  291): SecVideoCapture destructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): mSecCapture clear
I/SecMediaClock(  291): SecMediaClock destructor
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): ~StagefrightPlayer
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/AwesomePlayer(  291): destructor
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/MediaPlayer( 7957): decode(35, 19257568, 9226)
V/MediaPlayerService(  291): decode(30, 19257568, 9226)
,V/MediaPlayerService(  291): player type = 3
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): constructor
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): StagefrightPlayer
V/AwesomePlayer(  291): setListener
V/StagefrightPlayer(  291): initCheck
V/AwesomePlayer(  291): setAudioSink
V/StagefrightPlayer(  291): setDataSource(30, 19257568, 9226)
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
D/Utils   (  291): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  291): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  291): mBitrate = -1 bits/sec
I/OggExtractor(  291): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  291): current audio track index (0) is added to vector
V/AwesomePlayer(  291): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  291): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  291): prepare
V/AwesomePlayer(  291): prepareAsync
V/MediaPlayerService(  291): wait for prepare
,V/AwesomePlayer(  291): onPrepareAsyncEvent
I/SecMediaClock(  291): SecMediaClock constructor
I/SecMediaClock(  291): reset
I/SecVideoCapture(  291): SecVideoCapture constructor
I/ActivityManager(  891): Killing 6995:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): initAudioDecoder
V/AwesomePlayer(  291): checkOffloadExceptions is true
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  291): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  291): finishAsyncPrepare_l
V/AwesomePlayer(  291): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 200, 973, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 5, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  291): notify(0xb0724a60, 1, 0, 0)
V/AudioCache(  291): prepared
V/AudioCache(  291): wait - success
V/MediaPlayerService(  291): start
V/StagefrightPlayer(  291): start
V/AwesomePlayer(  291): play
,V/AwesomePlayer(  291): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  291): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  291): start of Playback, useOffload 0
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  291): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  291): Audio channels(2)
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  291): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  291): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 6, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): addBatteryData
I/AudioPlayer(  291): First fillBuffer call!!
,V/MediaPlayerService(  291): wait for playback complete
,D/AdaptiveEventManager( 1168): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1168): M updateContainers()
D/AdaptiveEventContainerSmall( 1168): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1168): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1168): pedoEvent == null
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] End Of Stream
,E/DatabaseUtils(  891): Writing exception to parcel
E/DatabaseUtils(  891): java.lang.NullPointerException: key == null
E/DatabaseUtils(  891): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  891): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  891): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  891): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  891): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  891): 	at android.os.Binder.execTransact(Binder.java:446)
,V/AwesomePlayer(  291): postAudioEOS delayUs (0)
,I/UpdateIcingCorporaServi( 1570): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,V/AwesomePlayer(  291): onCheckAudioStatus
V/AwesomePlayer(  291): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  291): onStreamDone
V/AwesomePlayer(  291): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  291): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache(  291): notify(0xb0724a60, 2, 0, 0)
V/AudioCache(  291): playback complete - thread will wake up later
V/AwesomePlayer(  291): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 7, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=1)
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,V/AudioCache(  291): wait - success
,V/AwesomePlayer(  291): addBatteryData
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
,V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
D/AudioPlayer(  291): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop() sendCommand(0x76, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  291): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  291): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  291): ~OggSource --
,I/OggExtractor(  291): ~OggExtractor ++
I/OggExtractor(  291): ~MyVorbisExtractor ++ 
I/OggExtractor(  291): ~MyVorbisExtractor --
I/OggExtractor(  291): ~OggExtractor --
,I/AudioPlayer(  291): reset out
,V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  291): SecVideoCapture destructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): mSecCapture clear
I/SecMediaClock(  291): SecMediaClock destructor
V/AwesomePlayer(  291): mSecMediaClock clear
,V/StagefrightPlayer(  291): ~StagefrightPlayer
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
,V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/AwesomePlayer(  291): destructor
,V/AwesomePlayer(  291): reset_l()
,V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
,V/MediaPlayer( 7957): decode(36, 19364180, 4890)
,V/MediaPlayerService(  291): decode(30, 19364180, 4890)
,V/MediaPlayerService(  291): player type = 3
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): constructor
,E/Zygote  ( 8036): MountEmulatedStorage()
E/Zygote  ( 8036): v2
I/libpersona( 8036): KNOX_SDCARD checking this for 10075
I/libpersona( 8036): KNOX_SDCARD not a persona
,V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): StagefrightPlayer
V/AwesomePlayer(  291): setListener
V/StagefrightPlayer(  291): initCheck
V/AwesomePlayer(  291): setAudioSink
V/StagefrightPlayer(  291): setDataSource(30, 19364180, 4890)
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb08140b0, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
D/Utils   (  291): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  291): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  291): mBitrate = -1 bits/sec
I/OggExtractor(  291): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  291): current audio track index (0) is added to vector
V/AwesomePlayer(  291): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  291): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  291): prepare
V/AwesomePlayer(  291): prepareAsync
V/MediaPlayerService(  291): wait for prepare
,V/AwesomePlayer(  291): onPrepareAsyncEvent
I/SecMediaClock(  291): SecMediaClock constructor
I/SecMediaClock(  291): reset
I/SecVideoCapture(  291): SecVideoCapture constructor
I/SecVideoCapture(  291): reset
,V/AwesomePlayer(  291): initAudioDecoder
V/AwesomePlayer(  291): checkOffloadExceptions is true
,I/ActivityManager(  891): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8036 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  291): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  291): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/SELinux ( 8036): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  291): finishAsyncPrepare_l
V/AwesomePlayer(  291): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  291): notify(0xb08140b0, 200, 973, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb08140b0, 5, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb08140b0, 1, 0, 0)
V/AudioCache(  291): prepared
V/AudioCache(  291): wait - success
V/MediaPlayerService(  291): start
V/StagefrightPlayer(  291): start
V/AwesomePlayer(  291): play
V/AwesomePlayer(  291): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  291): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  291): start of Playback, useOffload 0
,I/SELinux ( 8036): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8036): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  291): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  291): Audio channels(1)
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  291): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  291): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb08140b0, 6, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): addBatteryData
V/MediaPlayerService(  291): wait for playback complete
,I/AudioPlayer(  291): First fillBuffer call!!
,I/AudioPlayer(  291): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  291): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  291): postAudioEOS delayUs (0)
V/AwesomePlayer(  291): onCheckAudioStatus
V/AwesomePlayer(  291): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  291): onStreamDone
V/AwesomePlayer(  291): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  291): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb08140b0, 2, 0, 0)
V/AudioCache(  291): playback complete - thread will wake up later
V/AwesomePlayer(  291): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb08140b0, 7, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  291): addBatteryData
V/AudioCache(  291): wait - success
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb08140b0, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
D/AudioPlayer(  291): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop() sendCommand(0x77, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  291): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  291): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  291): ~OggSource --
I/OggExtractor(  291): ~OggExtractor ++
I/OggExtractor(  291): ~MyVorbisExtractor ++ 
I/OggExtractor(  291): ~MyVorbisExtractor --
I/OggExtractor(  291): ~OggExtractor --
,I/AudioPlayer(  291): reset out
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  291): SecVideoCapture destructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): mSecCapture clear
I/SecMediaClock(  291): SecMediaClock destructor
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): ~StagefrightPlayer
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/AwesomePlayer(  291): destructor
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/MediaPlayer( 7957): decode(37, 19290344, 17329)
V/MediaPlayerService(  291): decode(30, 19290344, 17329)
,V/MediaPlayerService(  291): player type = 3
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): constructor
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): StagefrightPlayer
V/AwesomePlayer(  291): setListener
V/StagefrightPlayer(  291): initCheck
V/AwesomePlayer(  291): setAudioSink
V/StagefrightPlayer(  291): setDataSource(30, 19290344, 17329)
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
D/Utils   (  291): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  291): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  291): mBitrate = -1 bits/sec
I/OggExtractor(  291): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  291): current audio track index (0) is added to vector
V/AwesomePlayer(  291): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  291): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  291): prepare
V/AwesomePlayer(  291): prepareAsync
V/MediaPlayerService(  291): wait for prepare
V/AwesomePlayer(  291): onPrepareAsyncEvent
I/SecMediaClock(  291): SecMediaClock constructor
I/SecMediaClock(  291): reset
I/SecVideoCapture(  291): SecVideoCapture constructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): initAudioDecoder
V/AwesomePlayer(  291): checkOffloadExceptions is true
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  291): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  291): finishAsyncPrepare_l
V/AwesomePlayer(  291): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 200, 973, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 5, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 1, 0, 0)
V/AudioCache(  291): prepared
V/AudioCache(  291): wait - success
V/MediaPlayerService(  291): start
V/StagefrightPlayer(  291): start
V/AwesomePlayer(  291): play
V/AwesomePlayer(  291): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  291): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  291): start of Playback, useOffload 0
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  291): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  291): Audio channels(2)
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  291): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  291): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 6, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): addBatteryData
V/MediaPlayerService(  291): wait for playback complete
,D/TimaKeyStoreProvider( 8036): TimaSignature is unavailable
,D/ActivityThread( 8036): Added TimaKeyStore provider
,I/AudioPlayer(  291): First fillBuffer call!!
,I/AudioPlayer(  291): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  291): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  291): postAudioEOS delayUs (0)
,D/ResourcesManager( 8036): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,V/AwesomePlayer(  291): onCheckAudioStatus
V/AwesomePlayer(  291): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  291): onStreamDone
V/AwesomePlayer(  291): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  291): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 2, 0, 0)
V/AudioCache(  291): playback complete - thread will wake up later
V/AwesomePlayer(  291): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 7, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  291): addBatteryData
V/AudioCache(  291): wait - success
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
D/AudioPlayer(  291): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/UpdateIcingCorporaServi( 1570): UpdateCorporaTask done [took 82 ms] updated apps [took 82 ms] 
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  291): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  291): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  291): ~OggSource --
I/OggExtractor(  291): ~OggExtractor ++
I/OggExtractor(  291): ~MyVorbisExtractor ++ 
I/OggExtractor(  291): ~MyVorbisExtractor --
I/OggExtractor(  291): ~OggExtractor --
,I/AudioPlayer(  291): reset out
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  291): SecVideoCapture destructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): mSecCapture clear
I/SecMediaClock(  291): SecMediaClock destructor
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): ~StagefrightPlayer
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/AwesomePlayer(  291): destructor
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/MediaPlayer( 7957): decode(38, 19190536, 6644)
V/MediaPlayerService(  291): decode(30, 19190536, 6644)
,V/MediaPlayerService(  291): player type = 3
,V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): constructor
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
,V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): StagefrightPlayer
V/AwesomePlayer(  291): setListener
V/StagefrightPlayer(  291): initCheck
V/AwesomePlayer(  291): setAudioSink
,V/StagefrightPlayer(  291): setDataSource(30, 19190536, 6644)
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
D/Utils   (  291): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  291): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  291): mBitrate = -1 bits/sec
I/OggExtractor(  291): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  291): current audio track index (0) is added to vector
,V/AwesomePlayer(  291): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  291): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  291): prepare
V/AwesomePlayer(  291): prepareAsync
V/MediaPlayerService(  291): wait for prepare
V/AwesomePlayer(  291): onPrepareAsyncEvent
I/SecMediaClock(  291): SecMediaClock constructor
,I/SecMediaClock(  291): reset
I/SecVideoCapture(  291): SecVideoCapture constructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): initAudioDecoder
V/AwesomePlayer(  291): checkOffloadExceptions is true
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
,V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  291): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
W/libprocessgroup(  891): failed to open /acct/uid_10020/pid_6977/cgroup.procs: No such file or directory
,V/AwesomePlayer(  291): finishAsyncPrepare_l
V/AwesomePlayer(  291): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 200, 973, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 5, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 1, 0, 0)
V/AudioCache(  291): prepared
V/AudioCache(  291): wait - success
V/MediaPlayerService(  291): start
V/StagefrightPlayer(  291): start
V/AwesomePlayer(  291): play
V/AwesomePlayer(  291): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  291): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  291): start of Playback, useOffload 0
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  291): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  291): Audio channels(1)
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  291): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  291): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 6, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): addBatteryData
I/AudioPlayer(  291): First fillBuffer call!!
I/AudioPlayer(  291): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  291): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/MediaPlayerService(  291): wait for playback complete
,W/libprocessgroup(  891): failed to open /acct/uid_1000/pid_6995/cgroup.procs: No such file or directory
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  291): postAudioEOS delayUs (0)
D/FileShare-Server( 8036): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,V/AwesomePlayer(  291): onCheckAudioStatus
V/AwesomePlayer(  291): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  291): onStreamDone
V/AwesomePlayer(  291): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  291): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 2, 0, 0)
V/AudioCache(  291): playback complete - thread will wake up later
V/AwesomePlayer(  291): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 7, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  291): addBatteryData
V/AudioCache(  291): wait - success
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
D/AudioPlayer(  291): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop() sendCommand(0x79, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  291): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  291): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  291): ~OggSource --
I/OggExtractor(  291): ~OggExtractor ++
I/OggExtractor(  291): ~MyVorbisExtractor ++ 
I/OggExtractor(  291): ~MyVorbisExtractor --
I/OggExtractor(  291): ~OggExtractor --
,I/AudioPlayer(  291): reset out
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  291): SecVideoCapture destructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): mSecCapture clear
I/SecMediaClock(  291): SecMediaClock destructor
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): ~StagefrightPlayer
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/AwesomePlayer(  291): destructor
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/MediaPlayer( 7957): decode(40, 19266876, 23389)
V/MediaPlayerService(  291): decode(30, 19266876, 23389)
,V/MediaPlayerService(  291): player type = 3
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): constructor
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): StagefrightPlayer
V/AwesomePlayer(  291): setListener
V/StagefrightPlayer(  291): initCheck
V/AwesomePlayer(  291): setAudioSink
V/StagefrightPlayer(  291): setDataSource(30, 19266876, 23389)
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
D/Utils   (  291): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  291): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  291): mBitrate = -1 bits/sec
I/OggExtractor(  291): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  291): current audio track index (0) is added to vector
V/AwesomePlayer(  291): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  291): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  291): prepare
V/AwesomePlayer(  291): prepareAsync
V/MediaPlayerService(  291): wait for prepare
,V/AwesomePlayer(  291): onPrepareAsyncEvent
I/SecMediaClock(  291): SecMediaClock constructor
I/SecMediaClock(  291): reset
I/SecVideoCapture(  291): SecVideoCapture constructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): initAudioDecoder
V/AwesomePlayer(  291): checkOffloadExceptions is true
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
,I/AwesomePlayer(  291): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  291): finishAsyncPrepare_l
V/AwesomePlayer(  291): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 200, 973, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 5, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 1, 0, 0)
V/AudioCache(  291): prepared
V/AudioCache(  291): wait - success
V/MediaPlayerService(  291): start
V/StagefrightPlayer(  291): start
,V/AwesomePlayer(  291): play
V/AwesomePlayer(  291): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  291): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  291): start of Playback, useOffload 0
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  291): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  291): Audio channels(2)
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  291): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  291): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 6, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): addBatteryData
I/AudioPlayer(  291): First fillBuffer call!!
I/AudioPlayer(  291): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  291): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,V/MediaPlayerService(  291): wait for playback complete
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8068): MountEmulatedStorage()
,E/Zygote  ( 8068): v2
I/libpersona( 8068): KNOX_SDCARD checking this for 1000
I/libpersona( 8068): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8068 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 7013:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  291): postAudioEOS delayUs (0)
,V/AwesomePlayer(  291): onCheckAudioStatus
,V/AwesomePlayer(  291): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  291): onStreamDone
V/AwesomePlayer(  291): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  291): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 2, 0, 0)
,V/AudioCache(  291): playback complete - thread will wake up later
V/AwesomePlayer(  291): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 7, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  291): addBatteryData
V/AudioCache(  291): wait - success
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
,V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
D/AudioPlayer(  291): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  291): OggSource::stop() mExtractor ref count = 1
,I/OggExtractor(  291): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  291): ~OggSource --
I/OggExtractor(  291): ~OggExtractor ++
I/OggExtractor(  291): ~MyVorbisExtractor ++ 
I/OggExtractor(  291): ~MyVorbisExtractor --
I/OggExtractor(  291): ~OggExtractor --
,I/AudioPlayer(  291): reset out
,V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  291): SecVideoCapture destructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): mSecCapture clear
I/SecMediaClock(  291): SecMediaClock destructor
V/AwesomePlayer(  291): mSecMediaClock clear
,V/StagefrightPlayer(  291): ~StagefrightPlayer
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
,V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/AwesomePlayer(  291): destructor
,V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
,V/MediaPlayer( 7957): decode(41, 19156232, 8154)
,I/SELinux ( 8068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/MediaPlayerService(  291): decode(30, 19156232, 8154)
,I/SELinux ( 8068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,V/MediaPlayerService(  291): player type = 3
V/AwesomePlayer(  291): setDefault
E/SELinux ( 8068): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/AwesomePlayer(  291): constructor
,V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): StagefrightPlayer
,V/AwesomePlayer(  291): setListener
V/StagefrightPlayer(  291): initCheck
V/AwesomePlayer(  291): setAudioSink
V/StagefrightPlayer(  291): setDataSource(30, 19156232, 8154)
V/AwesomePlayer(  291): reset_l()
,V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
,V/AwesomePlayer(  291): mSecMediaClock clear
D/Utils   (  291): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  291): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  291): mBitrate = -1 bits/sec
I/OggExtractor(  291): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  291): current audio track index (0) is added to vector
V/AwesomePlayer(  291): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  291): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  291): prepare
,V/AwesomePlayer(  291): prepareAsync
V/MediaPlayerService(  291): wait for prepare
V/AwesomePlayer(  291): onPrepareAsyncEvent
I/SecMediaClock(  291): SecMediaClock constructor
I/SecMediaClock(  291): reset
I/SecVideoCapture(  291): SecVideoCapture constructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): initAudioDecoder
V/AwesomePlayer(  291): checkOffloadExceptions is true
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  291): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  291): finishAsyncPrepare_l
V/AwesomePlayer(  291): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 200, 973, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 5, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 1, 0, 0)
V/AudioCache(  291): prepared
V/AudioCache(  291): wait - success
V/MediaPlayerService(  291): start
V/StagefrightPlayer(  291): start
,V/AwesomePlayer(  291): play
V/AwesomePlayer(  291): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  291): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  291): start of Playback, useOffload 0
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  291): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  291): Audio channels(1)
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  291): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  291): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 6, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): addBatteryData
I/AudioPlayer(  291): First fillBuffer call!!
V/MediaPlayerService(  291): wait for playback complete
,I/AudioPlayer(  291): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  291): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  291): postAudioEOS delayUs (0)
,V/AwesomePlayer(  291): onCheckAudioStatus
V/AwesomePlayer(  291): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  291): onStreamDone
V/AwesomePlayer(  291): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  291): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 2, 0, 0)
V/AudioCache(  291): playback complete - thread will wake up later
V/AwesomePlayer(  291): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 7, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  291): addBatteryData
V/AudioCache(  291): wait - success
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
D/AudioPlayer(  291): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop() sendCommand(0x7b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  291): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  291): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  291): ~OggSource --
I/OggExtractor(  291): ~OggExtractor ++
I/OggExtractor(  291): ~MyVorbisExtractor ++ 
I/OggExtractor(  291): ~MyVorbisExtractor --
I/OggExtractor(  291): ~OggExtractor --
,D/TimaKeyStoreProvider( 8068): TimaSignature is unavailable
,I/AudioPlayer(  291): reset out
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  291): SecVideoCapture destructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): mSecCapture clear
I/SecMediaClock(  291): SecMediaClock destructor
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): ~StagefrightPlayer
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/AwesomePlayer(  291): destructor
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/MediaPlayer( 7957): decode(42, 19129712, 4804)
,V/MediaPlayerService(  291): decode(30, 19129712, 4804)
,V/MediaPlayerService(  291): player type = 3
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): constructor
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): StagefrightPlayer
V/AwesomePlayer(  291): setListener
V/StagefrightPlayer(  291): initCheck
V/AwesomePlayer(  291): setAudioSink
V/StagefrightPlayer(  291): setDataSource(30, 19129712, 4804)
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb08140b0, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
D/Utils   (  291): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  291): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  291): mBitrate = -1 bits/sec
I/OggExtractor(  291): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  291): current audio track index (0) is added to vector
V/AwesomePlayer(  291): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  291): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  291): prepare
V/AwesomePlayer(  291): prepareAsync
V/MediaPlayerService(  291): wait for prepare
,V/AwesomePlayer(  291): onPrepareAsyncEvent
I/SecMediaClock(  291): SecMediaClock constructor
,I/SecMediaClock(  291): reset
I/SecVideoCapture(  291): SecVideoCapture constructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): initAudioDecoder
V/AwesomePlayer(  291): checkOffloadExceptions is true
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
,V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  291): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  291): finishAsyncPrepare_l
V/AwesomePlayer(  291): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  291): notify(0xb08140b0, 200, 973, 0)
,V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb08140b0, 5, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb08140b0, 1, 0, 0)
V/AudioCache(  291): prepared
V/AudioCache(  291): wait - success
,V/MediaPlayerService(  291): start
V/StagefrightPlayer(  291): start
V/AwesomePlayer(  291): play
V/AwesomePlayer(  291): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  291): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  291): start of Playback, useOffload 0
,D/ActivityThread( 8068): Added TimaKeyStore provider
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  291): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  291): Audio channels(1)
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  291): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  291): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb08140b0, 6, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): addBatteryData
V/MediaPlayerService(  291): wait for playback complete
,I/AudioPlayer(  291): First fillBuffer call!!
,I/AudioPlayer(  291): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  291): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  291): postAudioEOS delayUs (0)
V/AwesomePlayer(  291): onCheckAudioStatus
V/AwesomePlayer(  291): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  291): onStreamDone
V/AwesomePlayer(  291): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  291): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb08140b0, 2, 0, 0)
V/AudioCache(  291): playback complete - thread will wake up later
V/AwesomePlayer(  291): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb08140b0, 7, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  291): addBatteryData
V/AudioCache(  291): wait - success
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb08140b0, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
D/AudioPlayer(  291): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,W/libprocessgroup(  891): failed to open /acct/uid_10112/pid_7013/cgroup.procs: No such file or directory
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  291): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  291): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  291): ~OggSource --
I/OggExtractor(  291): ~OggExtractor ++
I/OggExtractor(  291): ~MyVorbisExtractor ++ 
I/OggExtractor(  291): ~MyVorbisExtractor --
I/OggExtractor(  291): ~OggExtractor --
,I/AudioPlayer(  291): reset out
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  291): SecVideoCapture destructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): mSecCapture clear
I/SecMediaClock(  291): SecMediaClock destructor
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): ~StagefrightPlayer
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/AwesomePlayer(  291): destructor
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/MediaPlayer( 7957): decode(43, 19099164, 9400)
V/MediaPlayerService(  291): decode(30, 19099164, 9400)
,V/MediaPlayerService(  291): player type = 3
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): constructor
,V/AwesomePlayer(  291): setDefault
,V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): StagefrightPlayer
V/AwesomePlayer(  291): setListener
V/StagefrightPlayer(  291): initCheck
,V/AwesomePlayer(  291): setAudioSink
V/StagefrightPlayer(  291): setDataSource(30, 19099164, 9400)
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 8, 0, 0)
V/AudioCache(  291): ignored
,V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
,D/Utils   (  291): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  291): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  291): mBitrate = -1 bits/sec
I/OggExtractor(  291): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  291): current audio track index (0) is added to vector
V/AwesomePlayer(  291): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer(  291): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  291): prepare
V/AwesomePlayer(  291): prepareAsync
V/MediaPlayerService(  291): wait for prepare
,V/AwesomePlayer(  291): onPrepareAsyncEvent
,I/SecMediaClock(  291): SecMediaClock constructor
I/SecMediaClock(  291): reset
I/SecVideoCapture(  291): SecVideoCapture constructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): initAudioDecoder
,V/AwesomePlayer(  291): checkOffloadExceptions is true
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  291): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  291): finishAsyncPrepare_l
V/AwesomePlayer(  291): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 200, 973, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 5, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 1, 0, 0)
V/AudioCache(  291): prepared
V/AudioCache(  291): wait - success
V/MediaPlayerService(  291): start
V/StagefrightPlayer(  291): start
V/AwesomePlayer(  291): play
V/AwesomePlayer(  291): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  291): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  291): start of Playback, useOffload 0
I/OMXCodec(  291): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  291): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  291): Audio channels(1)
,I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  291): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  291): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/MediaPlayer( 7957): decode(49, 19172584, 4112)
,V/MediaPlayerService(  291): decode(37, 19172584, 4112)
V/AudioCache(  291): notify(0xb0417650, 6, 0, 0)
I/AudioPlayer(  291): First fillBuffer call!!
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): addBatteryData
I/AudioPlayer(  291): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
V/MediaPlayerService(  291): player type = 3
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): constructor
V/AwesomePlayer(  291): setDefault
V/MediaPlayerService(  291): wait for playback complete
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): StagefrightPlayer
V/AwesomePlayer(  291): setListener
V/StagefrightPlayer(  291): initCheck
V/AwesomePlayer(  291): setAudioSink
V/StagefrightPlayer(  291): setDataSource(37, 19172584, 4112)
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
D/Utils   (  291): printFileName fd(38) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/AudioPlayer(  291): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
V/AwesomePlayer(  291): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  291): mBitrate = -1 bits/sec
I/OggExtractor(  291): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  291): current audio track index (0) is added to vector
V/AwesomePlayer(  291): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  291): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  291): prepare
V/AwesomePlayer(  291): prepareAsync
V/MediaPlayerService(  291): wait for prepare
,D/ResourcesManager( 8068): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,V/AwesomePlayer(  291): onPrepareAsyncEvent
I/SecMediaClock(  291): SecMediaClock constructor
I/SecMediaClock(  291): reset
I/SecVideoCapture(  291): SecVideoCapture constructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): initAudioDecoder
V/AwesomePlayer(  291): checkOffloadExceptions is true
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  291): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  291): finishAsyncPrepare_l
V/AwesomePlayer(  291): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 200, 973, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 5, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 1, 0, 0)
V/AudioCache(  291): prepared
V/AudioCache(  291): wait - success
V/MediaPlayerService(  291): start
V/StagefrightPlayer(  291): start
V/AwesomePlayer(  291): play
V/AwesomePlayer(  291): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  291): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  291): start of Playback, useOffload 0
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  291): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  291): Audio channels(1)
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  291): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  291): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 6, 0, 0)
I/AudioPlayer(  291): First fillBuffer call!!
I/AudioPlayer(  291): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  291): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  291): postAudioEOS delayUs (0)
V/AwesomePlayer(  291): onCheckAudioStatus
,V/AudioCache(  291): ignored
V/AwesomePlayer(  291): addBatteryData
V/MediaPlayerService(  291): wait for playback complete
V/AwesomePlayer(  291): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  291): onStreamDone
V/AwesomePlayer(  291): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  291): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 2, 0, 0)
V/AudioCache(  291): playback complete - thread will wake up later
V/AwesomePlayer(  291): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 7, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  291): addBatteryData
,V/AudioCache(  291): wait - success
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  291): mAudioTrackVector clear
D/AudioPlayer(  291): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  291): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  291): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor(  291): ~OggSource --
I/OggExtractor(  291): ~OggExtractor ++
I/OggExtractor(  291): ~MyVorbisExtractor ++ 
I/OggExtractor(  291): ~MyVorbisExtractor --
I/OMXCodec(  291): [OMX.google.vorbis.decoder] End Of Stream
I/OggExtractor(  291): ~OggExtractor --
V/AwesomePlayer(  291): postAudioEOS delayUs (0)
V/AwesomePlayer(  291): onCheckAudioStatus
V/AwesomePlayer(  291): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  291): onStreamDone
V/AwesomePlayer(  291): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  291): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 2, 0, 0)
V/AudioCache(  291): playback complete - thread will wake up later
V/AwesomePlayer(  291): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 7, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  291): addBatteryData
V/AudioCache(  291): wait - success
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
D/AudioPlayer(  291): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  291): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  291): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  291): ~OggSource --
I/OggExtractor(  291): ~OggExtractor ++
I/OggExtractor(  291): ~MyVorbisExtractor ++ 
I/OggExtractor(  291): ~MyVorbisExtractor --
I/OggExtractor(  291): ~OggExtractor --
,I/AudioPlayer(  291): reset out
,V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  291): SecVideoCapture destructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): mSecCapture clear
I/SecMediaClock(  291): SecMediaClock destructor
V/AwesomePlayer(  291): mSecMediaClock clear
,V/StagefrightPlayer(  291): ~StagefrightPlayer
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
,V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/AwesomePlayer(  291): destructor
I/AudioPlayer(  291): reset out
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  291): SecVideoCapture destructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): mSecCapture clear
I/SecMediaClock(  291): SecMediaClock destructor
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): ~StagefrightPlayer
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/AwesomePlayer(  291): destructor
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/MediaPlayer( 7957): decode(44, 19307764, 52024)
V/MediaPlayerService(  291): decode(30, 19307764, 52024)
,V/MediaPlayerService(  291): player type = 3
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): constructor
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): StagefrightPlayer
V/AwesomePlayer(  291): setListener
V/StagefrightPlayer(  291): initCheck
V/AwesomePlayer(  291): setAudioSink
V/StagefrightPlayer(  291): setDataSource(30, 19307764, 52024)
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
D/Utils   (  291): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  291): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  291): mBitrate = -1 bits/sec
I/OggExtractor(  291): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  291): current audio track index (0) is added to vector
V/AwesomePlayer(  291): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  291): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  291): prepare
V/AwesomePlayer(  291): prepareAsync
V/MediaPlayerService(  291): wait for prepare
V/AwesomePlayer(  291): onPrepareAsyncEvent
I/SecMediaClock(  291): SecMediaClock constructor
I/SecMediaClock(  291): reset
I/SecVideoCapture(  291): SecVideoCapture constructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): initAudioDecoder
V/AwesomePlayer(  291): checkOffloadExceptions is true
V/AudioPolicyManager(  291): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  291): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  291): finishAsyncPrepare_l
V/AwesomePlayer(  291): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 200, 973, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 5, 0, 0)
,V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 1, 0, 0)
V/AudioCache(  291): prepared
V/AudioCache(  291): wait - success
V/MediaPlayerService(  291): start
V/StagefrightPlayer(  291): start
V/AwesomePlayer(  291): play
V/AwesomePlayer(  291): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  291): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  291): start of Playback, useOffload 0
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  291): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  291): Audio channels(2)
,I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  291): open(48000, 2, 0x0, 1, 0)
V/AwesomePlayer(  291): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 6, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): addBatteryData
,V/MediaPlayerService(  291): wait for playback complete
I/AudioPlayer(  291): First fillBuffer call!!
,D/ShortcutReceiver( 8068):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  891): Killing 7031:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  291): postAudioEOS delayUs (0)
,V/AwesomePlayer(  291): onCheckAudioStatus
,V/AwesomePlayer(  291): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  291): onStreamDone
V/AwesomePlayer(  291): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  291): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 2, 0, 0)
V/AudioCache(  291): playback complete - thread will wake up later
V/AwesomePlayer(  291): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  291): notify(0xb09091f0, 7, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  291): addBatteryData
V/AudioCache(  291): wait - success
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
,V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
D/AudioPlayer(  291): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  291): OggSource::stop() mExtractor ref count = 1
,I/OggExtractor(  291): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  291): ~OggSource --
I/OggExtractor(  291): ~OggExtractor ++
I/OggExtractor(  291): ~MyVorbisExtractor ++ 
I/OggExtractor(  291): ~MyVorbisExtractor --
,I/OggExtractor(  291): ~OggExtractor --
,I/AudioPlayer(  291): reset out
,V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  291): SecVideoCapture destructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): mSecCapture clear
I/SecMediaClock(  291): SecMediaClock destructor
,V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): ~StagefrightPlayer
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
,V/AwesomePlayer(  291): destructor
,V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
,V/AwesomePlayer(  291): mSecMediaClock clear
,D/PackageBroadcastService( 2413): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,V/MediaPlayer( 7957): decode(45, 19172584, 4112)
,V/MediaPlayerService(  291): decode(30, 19172584, 4112)
,V/MediaPlayerService(  291): player type = 3
,V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): constructor
D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthServiceInstalled() : HealthService is Installed.
,V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): StagefrightPlayer
V/AwesomePlayer(  291): setListener
V/StagefrightPlayer(  291): initCheck
V/AwesomePlayer(  291): setAudioSink
V/StagefrightPlayer(  291): setDataSource(30, 19172584, 4112)
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
D/Utils   (  291): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  291): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  291): mBitrate = -1 bits/sec
I/OggExtractor(  291): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  291): current audio track index (0) is added to vector
V/AwesomePlayer(  291): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  291): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  291): prepare
V/AwesomePlayer(  291): prepareAsync
V/MediaPlayerService(  291): wait for prepare
,V/AwesomePlayer(  291): onPrepareAsyncEvent
I/SecMediaClock(  291): SecMediaClock constructor
I/SecMediaClock(  291): reset
I/SecVideoCapture(  291): SecVideoCapture constructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): initAudioDecoder
V/AwesomePlayer(  291): checkOffloadExceptions is true
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/OMXCodec(  291): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  291): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  291): finishAsyncPrepare_l
V/AwesomePlayer(  291): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 200, 973, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 5, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 1, 0, 0)
V/AudioCache(  291): prepared
V/AudioCache(  291): wait - success
V/MediaPlayerService(  291): start
V/StagefrightPlayer(  291): start
V/AwesomePlayer(  291): play
V/AwesomePlayer(  291): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  291): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  291): start of Playback, useOffload 0
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  291): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  291): Audio channels(1)
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  291): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  291): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 6, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): addBatteryData
I/AudioPlayer(  291): First fillBuffer call!!
I/AudioPlayer(  291): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  291): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  291): postAudioEOS delayUs (0)
V/MediaPlayerService(  291): wait for playback complete
V/AwesomePlayer(  291): onCheckAudioStatus
V/AwesomePlayer(  291): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  291): onStreamDone
V/AwesomePlayer(  291): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  291): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 2, 0, 0)
V/AudioCache(  291): playback complete - thread will wake up later
V/AwesomePlayer(  291): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 7, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  291): addBatteryData
V/AudioCache(  291): wait - success
V/StagefrightPlayer(  291): reset
,V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0724a60, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
D/AudioPlayer(  291): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  291): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  291): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  291): ~OggSource --
I/OggExtractor(  291): ~OggExtractor ++
I/OggExtractor(  291): ~MyVorbisExtractor ++ 
I/OggExtractor(  291): ~MyVorbisExtractor --
I/OggExtractor(  291): ~OggExtractor --
,I/AudioPlayer(  291): reset out
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  291): SecVideoCapture destructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): mSecCapture clear
I/SecMediaClock(  291): SecMediaClock destructor
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): ~StagefrightPlayer
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/AwesomePlayer(  291): destructor
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/MediaPlayer( 7957): decode(46, 19235660, 21825)
V/MediaPlayerService(  291): decode(29, 19235660, 21825)
,V/MediaPlayerService(  291): player type = 3
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): constructor
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): StagefrightPlayer
V/AwesomePlayer(  291): setListener
V/StagefrightPlayer(  291): initCheck
V/AwesomePlayer(  291): setAudioSink
V/StagefrightPlayer(  291): setDataSource(29, 19235660, 21825)
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
D/Utils   (  291): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  291): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  291): mBitrate = -1 bits/sec
I/OggExtractor(  291): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  291): current audio track index (0) is added to vector
V/AwesomePlayer(  291): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  291): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  291): prepare
V/AwesomePlayer(  291): prepareAsync
V/MediaPlayerService(  291): wait for prepare
V/AwesomePlayer(  291): onPrepareAsyncEvent
I/SecMediaClock(  291): SecMediaClock constructor
I/SecMediaClock(  291): reset
I/SecVideoCapture(  291): SecVideoCapture constructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): initAudioDecoder
V/AwesomePlayer(  291): checkOffloadExceptions is true
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  291): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  291): finishAsyncPrepare_l
V/AwesomePlayer(  291): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 200, 973, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 5, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 1, 0, 0)
V/AudioCache(  291): prepared
V/AudioCache(  291): wait - success
V/MediaPlayerService(  291): start
V/StagefrightPlayer(  291): start
V/AwesomePlayer(  291): play
V/AwesomePlayer(  291): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  291): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  291): start of Playback, useOffload 0
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  291): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  291): Audio channels(2)
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  291): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  291): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 6, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): addBatteryData
V/MediaPlayerService(  291): wait for playback complete
I/AudioPlayer(  291): First fillBuffer call!!
I/AudioPlayer(  291): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  291): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/PeopleContactsSync( 2413): CP2 sync disabled
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  291): postAudioEOS delayUs (0)
,V/AwesomePlayer(  291): onCheckAudioStatus
V/AwesomePlayer(  291): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  291): onStreamDone
V/AwesomePlayer(  291): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  291): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 2, 0, 0)
,V/AudioCache(  291): playback complete - thread will wake up later
V/AwesomePlayer(  291): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 7, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  291): addBatteryData
V/AudioCache(  291): wait - success
,V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb09091f0, 8, 0, 0)
,V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
D/AudioPlayer(  291): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  291): OggSource::stop() mExtractor ref count = 1
,I/OggExtractor(  291): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  291): ~OggSource --
I/OggExtractor(  291): ~OggExtractor ++
I/OggExtractor(  291): ~MyVorbisExtractor ++ 
I/OggExtractor(  291): ~MyVorbisExtractor --
I/OggExtractor(  291): ~OggExtractor --
,I/AudioPlayer(  291): reset out
,V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  291): SecVideoCapture destructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): mSecCapture clear
I/SecMediaClock(  291): SecMediaClock destructor
V/AwesomePlayer(  291): mSecMediaClock clear
,V/StagefrightPlayer(  291): ~StagefrightPlayer
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/AwesomePlayer(  291): destructor
,V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
,V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
,V/MediaPlayer( 7957): decode(47, 19134596, 21552)
V/MediaPlayerService(  291): decode(30, 19134596, 21552)
,V/MediaPlayerService(  291): player type = 3
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): constructor
,V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): StagefrightPlayer
V/AwesomePlayer(  291): setListener
V/StagefrightPlayer(  291): initCheck
V/AwesomePlayer(  291): setAudioSink
V/StagefrightPlayer(  291): setDataSource(30, 19134596, 21552)
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
D/Utils   (  291): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  291): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  291): mBitrate = -1 bits/sec
I/OggExtractor(  291): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  291): current audio track index (0) is added to vector
V/AwesomePlayer(  291): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  291): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  291): prepare
V/AwesomePlayer(  291): prepareAsync
V/MediaPlayerService(  291): wait for prepare
V/AwesomePlayer(  291): onPrepareAsyncEvent
I/SecMediaClock(  291): SecMediaClock constructor
I/SecMediaClock(  291): reset
I/SecVideoCapture(  291): SecVideoCapture constructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): initAudioDecoder
V/AwesomePlayer(  291): checkOffloadExceptions is true
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  291): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  291): finishAsyncPrepare_l
V/AwesomePlayer(  291): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 200, 973, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 5, 0, 0)
,V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 1, 0, 0)
V/AudioCache(  291): prepared
V/AudioCache(  291): wait - success
V/MediaPlayerService(  291): start
V/StagefrightPlayer(  291): start
V/AwesomePlayer(  291): play
,V/AwesomePlayer(  291): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  291): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  291): start of Playback, useOffload 0
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  291): Audio channels(2)
,I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  291): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  291): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 6, 0, 0)
V/AudioCache(  291): ignored
,V/AwesomePlayer(  291): addBatteryData
I/AudioPlayer(  291): First fillBuffer call!!
I/AudioPlayer(  291): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  291): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
V/MediaPlayerService(  291): wait for playback complete
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  291): postAudioEOS delayUs (0)
,V/AwesomePlayer(  291): onCheckAudioStatus
V/AwesomePlayer(  291): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  291): onStreamDone
V/AwesomePlayer(  291): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  291): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 2, 0, 0)
,V/AudioCache(  291): playback complete - thread will wake up later
V/AwesomePlayer(  291): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 7, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  291): addBatteryData
V/AudioCache(  291): wait - success
V/StagefrightPlayer(  291): reset
,V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb04174c0, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
D/AudioPlayer(  291): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  291): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  291): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  291): ~OggSource --
I/OggExtractor(  291): ~OggExtractor ++
,I/OggExtractor(  291): ~MyVorbisExtractor ++ 
I/OggExtractor(  291): ~MyVorbisExtractor --
I/OggExtractor(  291): ~OggExtractor --
I/AudioPlayer(  291): reset out
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  291): SecVideoCapture destructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): mSecCapture clear
,I/SecMediaClock(  291): SecMediaClock destructor
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): ~StagefrightPlayer
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/AwesomePlayer(  291): destructor
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/MediaPlayer( 7957): decode(48, 19228560, 7017)
V/MediaPlayerService(  291): decode(30, 19228560, 7017)
V/MediaPlayerService(  291): player type = 3
V/AwesomePlayer(  291): setDefault
,V/AwesomePlayer(  291): constructor
V/AwesomePlayer(  291): setDefault
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): StagefrightPlayer
V/AwesomePlayer(  291): setListener
V/StagefrightPlayer(  291): initCheck
V/AwesomePlayer(  291): setAudioSink
V/StagefrightPlayer(  291): setDataSource(30, 19228560, 7017)
V/AwesomePlayer(  291): reset_l()
,V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  291): mSecCapture clear
,V/AwesomePlayer(  291): mSecMediaClock clear
D/Utils   (  291): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  291): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  291): mBitrate = -1 bits/sec
I/OggExtractor(  291): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  291): current audio track index (0) is added to vector
V/AwesomePlayer(  291): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  291): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService(  291): prepare
V/AwesomePlayer(  291): prepareAsync
V/MediaPlayerService(  291): wait for prepare
V/AwesomePlayer(  291): onPrepareAsyncEvent
I/SecMediaClock(  291): SecMediaClock constructor
I/SecMediaClock(  291): reset
I/SecVideoCapture(  291): SecVideoCapture constructor
I/SecVideoCapture(  291): reset
,V/AwesomePlayer(  291): initAudioDecoder
V/AwesomePlayer(  291): checkOffloadExceptions is true
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  291): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
,I/AwesomePlayer(  291): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  291): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  291): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  291): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  291): finishAsyncPrepare_l
,V/AwesomePlayer(  291): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 200, 973, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 5, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 1, 0, 0)
,V/AudioCache(  291): prepared
V/AudioCache(  291): wait - success
V/MediaPlayerService(  291): start
V/StagefrightPlayer(  291): start
V/AwesomePlayer(  291): play
V/AwesomePlayer(  291): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  291): startAudioPlayer_l, sendErrorNotification (0)
,D/AudioPlayer(  291): start of Playback, useOffload 0
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
W/libprocessgroup(  891): failed to open /acct/uid_10118/pid_7031/cgroup.procs: No such file or directory
I/OMXCodec(  291): >>>UHQA initOutputFormat 16
I/OMXCodec(  291): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  291): Audio channels(2)
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  291): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  291): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  291): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 6, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): addBatteryData
I/AudioPlayer(  291): First fillBuffer call!!
I/AudioPlayer(  291): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  291): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
V/MediaPlayerService(  291): wait for playback complete
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  291): postAudioEOS delayUs (0)
,V/AwesomePlayer(  291): onCheckAudioStatus
V/AwesomePlayer(  291): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  291): onStreamDone
V/AwesomePlayer(  291): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  291): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 2, 0, 0)
V/AudioCache(  291): playback complete - thread will wake up later
,V/AwesomePlayer(  291): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 7, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  291): addBatteryData
V/AudioCache(  291): wait - success
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
,V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  291): notify(0xb0417650, 8, 0, 0)
V/AudioCache(  291): ignored
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
D/AudioPlayer(  291): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  291): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  291): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  291): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  291): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  291): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  291): ~OggSource --
I/OggExtractor(  291): ~OggExtractor ++
I/OggExtractor(  291): ~MyVorbisExtractor ++ 
,I/OggExtractor(  291): ~MyVorbisExtractor --
I/OggExtractor(  291): ~OggExtractor --
I/AudioPlayer(  291): reset out
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  291): SecVideoCapture destructor
I/SecVideoCapture(  291): reset
V/AwesomePlayer(  291): mSecCapture clear
I/SecMediaClock(  291): SecMediaClock destructor
,V/AwesomePlayer(  291): mSecMediaClock clear
V/StagefrightPlayer(  291): ~StagefrightPlayer
V/StagefrightPlayer(  291): reset
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
V/AwesomePlayer(  291): destructor
V/AwesomePlayer(  291): reset_l()
V/AwesomePlayer(  291): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  291): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  291): mAudioTrackVector clear
V/AwesomePlayer(  291): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  291): mSecCapture clear
V/AwesomePlayer(  291): mSecMediaClock clear
,I/SecureStorage(  349): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage(  349): [INFO]: SPID(0x00000005)PID: 7981, TID: 7993
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,I/SecureStorage( 7981): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 7981): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,I/SecSQLiteOpenHelper( 7957): getWritableDatabase(pwd)
,I/SecSQLiteOpenHelper( 7957): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper( 7957): Open platform.db in secure mode
,D/SecSQLiteDatabase( 7957): Android Version: 5.0
,D/SecSQLiteDatabase( 7957): Load library secsqlite.so for Android 5.0
,I/SecSQLiteDatabase( 7957): openSecureDatabase...
,I/SecSQLiteDatabase( 7957): private openSecureDatabase...
,I/SecSQLiteConnectionPool( 7957): OpenSecure
I/SecSQLiteConnectionPool( 7957): OpenSecure with password
I/SecSQLiteConnectionPool( 7957): openSecureConnectionLocked
,I/SecSQLiteDatabase( 7957): ...private openSecureDatabase
I/SecSQLiteDatabase( 7957): ...openSecureDatabase
,I/SecSQLiteOpenHelper( 7957): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper( 7957): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7957): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/System.err( 7957): java.lang.NumberFormatException: Invalid int: "null"
,W/System.err( 7957): 	at java.lang.Integer.invalidInt(Integer.java:138)
,W/System.err( 7957): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 7957): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 7957): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:449)
W/System.err( 7957): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1173)
,W/System.err( 7957): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7957): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7957): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,E/SMD     (  284): DCD ON
,D/PreloadUpdateManagerStateMachine( 7127): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 7127): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7127): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7127): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  ( 7127): RestApi Request Add : 2307
,E/File    ( 7127): fail readDirectory() errno=2
,I/dhcpcd  ( 7636): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7636): wlan0: no IPv6 Routers available
,I/System.out( 7127): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 7127): (HTTPLog)-Static: isShipBuild true
,I/System.out( 7127): (HTTPLog)-Thread-1180-42861339: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/PreloadUpdateManagerStateMachine( 7127): execute::CHECK_TIMEOUT_FOR_UPDATE:EXECUTE
,I/qtaguid ( 7127): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 7127, getuid(): 10040
,I/qtaguid ( 7127): Untagging socket 26
,D/hcjo    ( 7127): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 7127): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 7127): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7127): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7127): entry::REQ_UPDATE_CHECK
,I/Volley  ( 7127): RestApi Request Add : 2315
,I/qtaguid ( 7127): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 7127, getuid(): 10040
,I/Atfwd_Sendcmd(  341): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  341): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,I/GAV3    ( 7957): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 400, PST = 426, CUR = 300
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,E/SMD     (  284): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/qtaguid ( 7127): Untagging socket -1
,I/qtaguid ( 7127): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 7127): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger( 7127): untagSocket(-1) failed with errno -9
,D/Volley  ( 7127): [1181] BasicNetwork.logSlowRequests: HTTP response for request=<[ ] https://pl-odc.samsungapps.com/ods.as 0x79a327ee NORMAL 2> [lifetime=5584], [size=300], [rc=200], [retryCount=0]
,D/Volley  ( 7127): [1] Request.a: 5596 ms: [ ] https://pl-odc.samsungapps.com/ods.as 0x79a327ee NORMAL 2
D/PreloadUpdateManagerStateMachine( 7127): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
D/PreloadUpdateManagerStateMachine( 7127): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 7127): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 7127): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 7127): entry::FINISH
,D/PreloadUpdateManagerStateMachine( 7127): exit::FINISH
D/PreloadUpdateManagerStateMachine( 7127): entry::IDLE
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,E/SMD     (  284): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,V/AlarmManager(  891): waitForAlarm result :4
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/FactoryTest( 6695): Not factory mode
D/FactoryTest( 6695): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6695): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6695): still no open session command from host, so toast
,W/ContextImpl( 6695): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6695): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6695): Timeline: Activity_launch_request id:com.android.settings time:117668
E/PersonaManagerService(  891): inState():  stateMachine is null !!
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  891): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  891): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 891  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  891): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
E/MTPRx   ( 6695): started activity for popup
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SQLiteSecureOpenHelper( 3558): getWritableDatabase(pwd)
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SQLiteSecureOpenHelper( 3558): getDatabaseLocked(b,b,pwd)...
,V/AlarmManager(  891): waitForAlarm result :4
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6695): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6695): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6695): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/InputMethodManagerService(  891): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/ActivityManager(  891): Invalid thumbnail dimensions: 576x576
,W/InputMethodManagerService(  891): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2e7f32c0 attribute=null, token = android.os.BinderProxy@35f06f51
,I/SQLiteSecureOpenHelper( 3558): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3558): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6695): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SettingsReceiverActivity( 6695): dev.kiessupport is : TRUE
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Activity( 6695): performCreate Call secproduct feature valuefalse
D/Activity( 6695): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ActivityManager(  891): post active user change for 0
D/KnoxTimeoutHandler(  891): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  891): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/Timeline( 7387): Timeline: Activity_idle id: android.os.BinderProxy@32ed2431 time:117928
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6558): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6558): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6558): [1] 5.onFinished: Scheduling replication attempt 3.
,I/art     (  891): Explicit concurrent mark sweep GC freed 76216(4MB) AllocSpace objects, 12(2MB) LOS objects, 29% free, 38MB/54MB, paused 1.229ms total 86.486ms
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 370, PST = 417, CUR = 300
,D/CustomFrequencyManagerService(  891): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 891  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  891): mDVFSHelper.release()
D/CustomFrequencyManagerService(  891): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 891  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/CustomFrequencyManagerService(  891): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 891  tag : ACTIVITY_RESUME_BOOSTER@10
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,E/SMD     (  284): DCD ON
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,I/ServiceManager(  341): Waiting for service AtCmdFwd...,
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/PowerManagerService(  891): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  891): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  891): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  891): lcd : 3 +
,D/lights  (  891): lcd : 3 -
,D/DisplayPowerController(  891): getFinalBrightness : 1 -> 1
D/lights  (  891): lcd : 1 +
,D/lights  (  891): lcd : 1 -
,D/DisplayPowerController(  891): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,E/SMD     (  284): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1168): applyOpen
,D/StatusBar.NetworkController( 1168): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1168): applyOpen
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,E/SMD     (  284): DCD ON
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  891): SIOP:: AP = 340, PST = 403, CUR = 300
,D/X       (  891): broadcastSiopLevelIntent:: currentSiopLevel = -1,
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/ContentApp( 1225):  LEVEL : -1
,I/SystemBroadcastReceiver( 7148): [#DCM#] [DCM_Performance] onReceive completed in time  1161 microsec. 
,I/SystemBroadcastReceiver( 7148): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7148): [#DCM#] onReceive action = EVENT_SIOP
,E/Zygote  ( 8165): MountEmulatedStorage()
,E/Zygote  ( 8165): v2
I/libpersona( 8165): KNOX_SDCARD checking this for 10054
I/libpersona( 8165): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8165 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 8165): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8165): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8165): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8165): TimaSignature is unavailable
,D/ActivityThread( 8165): Added TimaKeyStore provider
,D/ResourcesManager( 8165): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8165): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8165): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8165): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8165): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8165): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 8165): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8165): core_num = 4
,W/linker  ( 8165): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8165): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8165): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,D/videowall-Global( 8165): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/PowerManagerService(  891): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  891): Nap time (uid 1000)...
I/PowerManagerService(  891): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  891): Going to sleep due to screen timeout (uid 1000)...
,D/InputManager-JNI(  891): setDeviceInteractive: 0
,D/PowerManagerService(  891): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  891): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService(  891): handleSandman : startDream()
,D/InputManager-JNI(  891): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,E/PowerManagerService(  891): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  891): Sleeping (uid 1000)...
D/PowerManagerService(  891): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  891): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  891): [input device light] handleInputDeviceLightOff
,D/InputManager-JNI(  891): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/InputManager-JNI(  891): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  891): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  891): 	.unregisterCallback : 1, client=
D/SContextService(  891): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@2ab3b9d3, Service = Auto Rotation, used = 1
,W/CAE     (  891): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  891): stop(ContextProvider.java:149)
,V/CAE     (  891): clear(AutoRotationRunner.java:182)
,V/CAE     (  891): disable(AutoRotationRunner.java:171)
,I/CAE     (  891): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  891): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  297): sendContextData: -78, 7, 0, 0
,D/TranscodeReceiver( 8165):  SIOP_LEVEL: -1
,I/ActivityManager(  891): Killing 7047:com.samsung.helphub/1000 (adj 15): bgCount ##41
,D/CAE     (  891): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  891): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  891): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  891): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  891): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  891): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  891): removeSContextService() : service = Auto Rotation
D/SContextService(  891): ===== SContext Service List =====
D/SContextManager(  891):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@134040df, service=Auto Rotation
,I/SQLiteSecureOpenHelper( 3558): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3558): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 1168): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1168): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1168): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1168): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/KeyguardViewMediator( 1168): timeout : 5000
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/DisplayPowerController(  891): ColorFade: onAnimationStart
D/DisplayPowerController(  891): getFinalBrightness : 8 -> 0
,W/libprocessgroup(  891): failed to open /acct/uid_1000/pid_7047/cgroup.procs: No such file or directory
,D/lights  (  891): lcd : 0 +
,D/DisplayPowerController(  891): getFinalBrightness : 8 -> 0
,D/KeyguardViewMediator( 1168): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1168): handleNotifyScreenOff
,D/lights  (  891): lcd : 0 -
,D/LightsService(  891): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 891) 
D/LightsService(  891): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  891): [SvcLED]  onSensorChanged::light value = 3
,D/SensorManager(  891): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService(  891): turn on LED for fully charged
,D/SensorManager(  891): unregisterListener ::   
D/lights  (  891): led_pattern : 5 +
,I/CAE     (  891): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  891): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  891): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  891): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  297): sendContextData: -76, 13, -46, 0
,D/lights  (  891): led_pattern : 5 -
D/LightsService(  891): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  891): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 11, 46, 51,
D/SensorHubManager(  891): SendSensorHubData: send data = -63, 14, 11, 46, 51
D/Sensorhubs(  297): sendContextData: -63, 14, 11, 46, 51
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  891):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  891): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  891): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  891): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  891): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  891): do suspend true
,D/NotificationService(  891): ACTION_SCREEN_OFF
D/LightsService(  891): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 891) 
D/LightsService(  891): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  891): [SvcLED]  onSensorChanged::light value = 3
,D/SensorManager(  891): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  891): unregisterListener ::   
D/LightsService(  891): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=off
,V/voice   (  291): voice_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
,V/audio_hw_primary(  291): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  891): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  891): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  891): Bridge Server is not available
,D/VolumePanel( 1168): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1168): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1168): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1168): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  891): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  891): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1450): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1168):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1168): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1168): dismissHelpPopup 
,D/accuweather( 2061): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2061): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
,D/accuweather( 2061): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/ActivityManager(  891): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  891): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/DisplayPowerState(  891): !@ ColorFade entry
D/DisplayPowerController(  891): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  891): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/AutomaticBrightnessController(  891): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  891): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/AutomaticBrightnessController(  891): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  891): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,I/SystemBroadcastReceiver( 7148): [#DCM#] [DCM_Performance] onReceive completed in time  130 microsec. 
I/SystemBroadcastReceiver( 7148): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7148): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 7148): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/PowerManagerService(  891): [PWL] sb release: PowerManagerService.Broadcasts
,D/SensorManager(  891): unregisterListener ::   
,E/Sensors (  891): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  891): unregisterListener ::   
,D/SSRM:m  (  891): SIOP:: AP = 340, PST = 389, CUR = 300
,D/DisplayPowerController(  891): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  891): getFinalBrightness : 0 -> 0
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  891): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  891): Display changed displayId=0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/StatusBar.NetworkController( 1168): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1168): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1168): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/rmt_storage(  274): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
,I/rmt_storage(  274): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  274): wakelock acquired: 1, error no: 42
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229454592)
,E/SMD     (  284): DCD ON
,I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229454592) wakelock released: 1, error no: 22
I/rmt_storage(  274): 
,I/rmt_storage(  274): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  891): Excessive delay in setPowerMode(): 253ms
D/PowerManagerService(  891): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  891): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  891): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  891): Got set_interactive hint
,I/PowerManagerService(  891): [PWL] Off : 0s ago
I/PowerManagerService(  891): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  891): [PWL]     mDisplayReady : false
D/DisplayPowerController(  891): getFinalBrightness : 0 -> 0
D/PowerManagerService(  891): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  891): [PWL] sb release: PowerManagerService.Display
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  284): DCD ON
,E/Watchdog(  891): !@Sync 4
,V/AlarmManager(  891): waitForAlarm result :4
,D/KeyguardViewMediator( 1168): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/KeyguardViewMediator( 1168): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService(  891): [PWL] Off : 5s ago
,E/SMD     (  284): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/AlarmManager(  891): waitForAlarm result :4
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  891): stay LED for fully charged
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6558): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6558): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6558): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/AlarmManager(  891): waitForAlarm result :8
,E/SMD     (  284): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/SSRM:m  (  891): SIOP:: AP = 330, PST = 377, CUR = 300
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  284): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 15s ago
,E/SMD     (  284): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/SSRM:m  (  891): SIOP:: AP = 320, PST = 368, CUR = 300
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1658): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6528): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6528): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6528): 	at kfv.a(PG:65)
E/HttpOperation( 6528): 	at kff.u(PG:385)
E/HttpOperation( 6528): 	at kfb.a(PG:29)
E/HttpOperation( 6528): 	at kff.l(PG:132)
E/HttpOperation( 6528): 	at dsf.a(PG:807)
E/HttpOperation( 6528): 	at fhk.a(PG:1126)
E/HttpOperation( 6528): 	at fhk.a(PG:908)
E/HttpOperation( 6528): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6528): 	at ihi.a(PG:22)
E/HttpOperation( 6528): 	at kft.a(PG:91)
E/HttpOperation( 6528): 	at kfv.a(PG:62)
E/HttpOperation( 6528): 	... 8 more
E/HttpOperation( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6528): 	at gde.c(Unknown Source)
E/HttpOperation( 6528): 	at gde.b(Unknown Source)
E/HttpOperation( 6528): 	at ihi.a(PG:19)
E/HttpOperation( 6528): 	... 10 more
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,E/HttpOperation( 6528): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6528): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6528): 	at kfv.a(PG:65)
E/HttpOperation( 6528): 	at kff.u(PG:385)
E/HttpOperation( 6528): 	at kfb.a(PG:29)
E/HttpOperation( 6528): 	at kff.l(PG:132)
E/HttpOperation( 6528): 	at ieo.a(PG:43)
E/HttpOperation( 6528): 	at iep.a(PG:93)
E/HttpOperation( 6528): 	at fhn.a(PG:59)
E/HttpOperation( 6528): 	at lex.a(PG:85)
E/HttpOperation( 6528): 	at lex.b(PG:132)
E/HttpOperation( 6528): 	at fhk.a(PG:1146)
E/HttpOperation( 6528): 	at fhk.a(PG:908)
E/HttpOperation( 6528): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6528): 	at ihi.a(PG:22)
E/HttpOperation( 6528): 	at kft.a(PG:91)
E/HttpOperation( 6528): 	at kfv.a(PG:62)
E/HttpOperation( 6528): 	... 12 more
E/HttpOperation( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6528): 	at gde.c(Unknown Source)
E/HttpOperation( 6528): 	at gde.b(Unknown Source)
E/HttpOperation( 6528): 	at ihi.a(PG:19)
E/HttpOperation( 6528): 	... 14 more
,E/ExperimentLoader( 6528): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6528): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6528): 	at kfv.a(PG:65)
E/ExperimentLoader( 6528): 	at kff.u(PG:385)
E/ExperimentLoader( 6528): 	at kfb.a(PG:29)
E/ExperimentLoader( 6528): 	at kff.l(PG:132)
E/ExperimentLoader( 6528): 	at ieo.a(PG:43)
E/ExperimentLoader( 6528): 	at iep.a(PG:93)
E/ExperimentLoader( 6528): 	at fhn.a(PG:59)
E/ExperimentLoader( 6528): 	at lex.a(PG:85)
E/ExperimentLoader( 6528): 	at lex.b(PG:132)
E/ExperimentLoader( 6528): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6528): 	at fhk.a(PG:908)
E/ExperimentLoader( 6528): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6528): 	at ihi.a(PG:22)
E/ExperimentLoader( 6528): 	at kft.a(PG:91)
E/ExperimentLoader( 6528): 	at kfv.a(PG:62)
E/ExperimentLoader( 6528): 	... 12 more
E/ExperimentLoader( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6528): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6528): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6528): 	at ihi.a(PG:19)
E/ExperimentLoader( 6528): 	... 14 more
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6528): [getaccountstatus] Unexpected exception
E/HttpOperation( 6528): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6528): 	at kfv.a(PG:65)
E/HttpOperation( 6528): 	at kff.u(PG:385)
E/HttpOperation( 6528): 	at kfb.a(PG:29)
E/HttpOperation( 6528): 	at ixd.a(PG:248)
E/HttpOperation( 6528): 	at ixd.b(PG:206)
E/HttpOperation( 6528): 	at ixd.a(PG:175)
E/HttpOperation( 6528): 	at fig.a(PG:78)
E/HttpOperation( 6528): 	at lex.a(PG:85)
E/HttpOperation( 6528): 	at lex.b(PG:132)
E/HttpOperation( 6528): 	at fhk.a(PG:1146)
E/HttpOperation( 6528): 	at fhk.a(PG:908)
E/HttpOperation( 6528): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6528): 	at ihi.a(PG:22)
E/HttpOperation( 6528): 	at kft.a(PG:91)
E/HttpOperation( 6528): 	at kfv.a(PG:62)
E/HttpOperation( 6528): 	... 12 more
E/HttpOperation( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6528): 	at gde.c(Unknown Source)
E/HttpOperation( 6528): 	at gde.b(Unknown Source)
E/HttpOperation( 6528): 	at ihi.a(PG:19)
E/HttpOperation( 6528): 	... 14 more
,E/EsSyncAdapterService( 6528): Sync failure
E/EsSyncAdapterService( 6528): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6528): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6528): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6528): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6528): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6528): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6528): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6528): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6528): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6528): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6528): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6528): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6528): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6528): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6528): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6528): 	... 10 more
E/EsSyncAdapterService( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6528): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6528): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6528): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6528): 	... 12 more
E/EsSyncAdapterService( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6528): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6528): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6528): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6528): 	... 14 more
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,D/SyncManager(  891): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 150275, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  891): mCursor = null
,E/SMD     (  284): DCD ON
,E/SQLiteLog( 1658): (10) POSIX Error : 11 SQLite Error : 3850
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/AlarmManager(  891): waitForAlarm result :4
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6558): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6558): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6558): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,E/SMD     (  284): DCD ON
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  891): SIOP:: AP = 310, PST = 358, CUR = 300
,I/PowerManagerService(  891): [PWL] Off : 30s ago
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  284): DCD ON
,E/Watchdog(  891): !@Sync 5
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON,
,D/SSRM:m  (  891): SIOP:: AP = 310, PST = 350, CUR = 300
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  891): stay LED for fully charged
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1658): Vacuum at: now=1453981661207 tag=VacuumService
,I/GoogleURLConnFactory( 1658): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Uploader( 1658): No account for auth token provided
,I/System.out( 1658): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1658): (HTTPLog)-Static: isShipBuild true
I/System.out( 1658): (HTTPLog)-Thread-194-839244078: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6558): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6558): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6558): [1] 5.onFinished: Giving up after 6 failures.
,V/AlarmManager(  891): waitForAlarm result :4
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7311): Starting books sync, d
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRM:m  (  891): SIOP:: AP = 300, PST = 344, CUR = 300
,I/qtaguid ( 1658): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1658, getuid(): 10012
,D/ResourcesManager( 1658): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,I/PowerManagerService(  891): [PWL] Off : 50s ago
I/PowerManagerService(  891): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  891): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  891): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10012, pid=1658, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=342)
I/PowerManagerService(  891): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=891, ws=WorkSource{10082}) (elapsedTime=85)
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1658): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1658): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1658): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1658): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1658): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1658): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1658): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7311): Authentication error
E/BooksAccountManager( 7311): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7311): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7311): null auth token
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,I/qtaguid ( 1658): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1658, getuid(): 10012
,I/qtaguid ( 7311): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7311, getuid(): 10082
,E/SMD     (  284): DCD ON
,W/Uploader( 1658): No account for auth token provided
,I/qtaguid ( 1658): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1658, getuid(): 10012
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,I/qtaguid ( 7311): Untagging socket 34
,W/ApiaryClient( 7311): Error response from books API: {
W/ApiaryClient( 7311):  "error": {
W/ApiaryClient( 7311):   "errors": [
W/ApiaryClient( 7311):    {
W/ApiaryClient( 7311):     "domain": "global",
W/ApiaryClient( 7311):     "reason": "required",
W/ApiaryClient( 7311):     "message": "Login Required",
W/ApiaryClient( 7311):     "locationType": "header",
W/ApiaryClient( 7311):     "location": "Authorization"
W/ApiaryClient( 7311):    }
W/ApiaryClient( 7311):   ],
W/ApiaryClient( 7311):   "code": 401,
W/ApiaryClient( 7311):   "message": "Login Required"
W/ApiaryClient( 7311):  }
W/ApiaryClient( 7311): }
,W/ApiaryClient( 7311): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7311): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5584839620911125569&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7311): Headers suppressed
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Uploader( 1658): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1658): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1658): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1658): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1658): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1658): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1658): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1658): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1658): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1658): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1658): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1658): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1658): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/qtaguid ( 1658): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1658, getuid(): 10012
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1658): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1658): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1658): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1658): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1658): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1658): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1658): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7311): Authentication error
E/BooksAccountManager( 7311): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7311): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7311): null auth token
,I/qtaguid ( 7311): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7311, getuid(): 10082
,I/qtaguid ( 7311): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7311, getuid(): 10082
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/Uploader( 1658): No account for auth token provided
,I/qtaguid ( 1658): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1658, getuid(): 10012
,I/qtaguid ( 7311): Untagging socket 34
,W/ApiaryClient( 7311): Error response from books API: {
W/ApiaryClient( 7311):  "error": {
W/ApiaryClient( 7311):   "errors": [
W/ApiaryClient( 7311):    {
W/ApiaryClient( 7311):     "domain": "global",
W/ApiaryClient( 7311):     "reason": "required",
W/ApiaryClient( 7311):     "message": "Login Required",
W/ApiaryClient( 7311):     "locationType": "header",
W/ApiaryClient( 7311):     "location": "Authorization"
W/ApiaryClient( 7311):    }
W/ApiaryClient( 7311):   ],
W/ApiaryClient( 7311):   "code": 401,
W/ApiaryClient( 7311):   "message": "Login Required"
W/ApiaryClient( 7311):  }
W/ApiaryClient( 7311): }
,W/ApiaryClient( 7311): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7311): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5584839620911125569&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7311): Headers suppressed
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Uploader( 1658):  no longer exists, so no auth token.
,I/qtaguid ( 1658): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1658, getuid(): 10012
,E/SMD     (  284): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1658): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1658): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1658): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1658): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1658): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1658): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1658): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7311): Authentication error
E/BooksAccountManager( 7311): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7311): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7311): null auth token
,I/qtaguid ( 7311): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7311, getuid(): 10082
,E/SQLiteLog( 1658): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 7311): Untagging socket 34
,W/ApiaryClient( 7311): Error response from books API: {
W/ApiaryClient( 7311):  "error": {
W/ApiaryClient( 7311):   "errors": [
W/ApiaryClient( 7311):    {
W/ApiaryClient( 7311):     "domain": "global",
W/ApiaryClient( 7311):     "reason": "required",
W/ApiaryClient( 7311):     "message": "Login Required",
W/ApiaryClient( 7311):     "locationType": "header",
W/ApiaryClient( 7311):     "location": "Authorization"
W/ApiaryClient( 7311):    }
W/ApiaryClient( 7311):   ],
W/ApiaryClient( 7311):   "code": 401,
W/ApiaryClient( 7311):   "message": "Login Required"
W/ApiaryClient( 7311):  }
W/ApiaryClient( 7311): }
,W/ApiaryClient( 7311): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7311): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5584839620911125569&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7311): Headers suppressed
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/BooksSync( 7311): Soft error
E/BooksSync( 7311): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7311): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5584839620911125569&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7311): Headers suppressed
E/BooksSync( 7311): 
E/BooksSync( 7311): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7311): Sync error
E/BooksSync( 7311): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7311): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5584839620911125569&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7311): Headers suppressed
E/BooksSync( 7311): 
E/BooksSync( 7311): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7311): Finished books sync
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  891): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 153818, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  891): Explicit concurrent mark sweep GC freed 62987(3MB) AllocSpace objects, 33(983KB) LOS objects, 29% free, 38MB/54MB, paused 1.678ms total 144.047ms
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  891): mCursor = null
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,E/HttpOperation( 6528): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6528): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6528): 	at kfv.a(PG:65)
E/HttpOperation( 6528): 	at kff.u(PG:385)
E/HttpOperation( 6528): 	at kfb.a(PG:29)
E/HttpOperation( 6528): 	at kff.l(PG:132)
E/HttpOperation( 6528): 	at dsf.a(PG:807)
E/HttpOperation( 6528): 	at fhk.a(PG:1126)
E/HttpOperation( 6528): 	at fhk.a(PG:908)
E/HttpOperation( 6528): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6528): 	at ihi.a(PG:22)
E/HttpOperation( 6528): 	at kft.a(PG:91)
E/HttpOperation( 6528): 	at kfv.a(PG:62)
E/HttpOperation( 6528): 	... 8 more
E/HttpOperation( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6528): 	at gde.c(Unknown Source)
E/HttpOperation( 6528): 	at gde.b(Unknown Source)
E/HttpOperation( 6528): 	at ihi.a(PG:19)
E/HttpOperation( 6528): 	... 10 more
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/art     ( 1658): Explicit concurrent mark sweep GC freed 61307(3MB) AllocSpace objects, 49(3MB) LOS objects, 40% free, 18MB/30MB, paused 930us total 109.354ms
,D/ResourcesManager( 1658): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6528): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6528): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6528): 	at kfv.a(PG:65)
E/HttpOperation( 6528): 	at kff.u(PG:385)
E/HttpOperation( 6528): 	at kfb.a(PG:29)
E/HttpOperation( 6528): 	at kff.l(PG:132)
E/HttpOperation( 6528): 	at ieo.a(PG:43)
E/HttpOperation( 6528): 	at iep.a(PG:93)
E/HttpOperation( 6528): 	at fhn.a(PG:59)
E/HttpOperation( 6528): 	at lex.a(PG:85)
E/HttpOperation( 6528): 	at lex.b(PG:132)
E/HttpOperation( 6528): 	at fhk.a(PG:1146)
E/HttpOperation( 6528): 	at fhk.a(PG:908)
E/HttpOperation( 6528): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6528): 	at ihi.a(PG:22)
E/HttpOperation( 6528): 	at kft.a(PG:91)
E/HttpOperation( 6528): 	at kfv.a(PG:62)
E/HttpOperation( 6528): 	... 12 more
E/HttpOperation( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6528): 	at gde.c(Unknown Source)
E/HttpOperation( 6528): 	at gde.b(Unknown Source)
E/HttpOperation( 6528): 	at ihi.a(PG:19)
E/HttpOperation( 6528): 	... 14 more
,E/ExperimentLoader( 6528): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6528): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6528): 	at kfv.a(PG:65)
E/ExperimentLoader( 6528): 	at kff.u(PG:385)
E/ExperimentLoader( 6528): 	at kfb.a(PG:29)
E/ExperimentLoader( 6528): 	at kff.l(PG:132)
E/ExperimentLoader( 6528): 	at ieo.a(PG:43)
E/ExperimentLoader( 6528): 	at iep.a(PG:93)
E/ExperimentLoader( 6528): 	at fhn.a(PG:59)
E/ExperimentLoader( 6528): 	at lex.a(PG:85)
E/ExperimentLoader( 6528): 	at lex.b(PG:132)
E/ExperimentLoader( 6528): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6528): 	at fhk.a(PG:908)
E/ExperimentLoader( 6528): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6528): 	at ihi.a(PG:22)
E/ExperimentLoader( 6528): 	at kft.a(PG:91)
E/ExperimentLoader( 6528): 	at kfv.a(PG:62)
E/ExperimentLoader( 6528): 	... 12 more
E/ExperimentLoader( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6528): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6528): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6528): 	at ihi.a(PG:19)
E/ExperimentLoader( 6528): 	... 14 more
I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,E/SQLiteLog( 1658): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6528): [getaccountstatus] Unexpected exception
E/HttpOperation( 6528): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6528): 	at kfv.a(PG:65)
E/HttpOperation( 6528): 	at kff.u(PG:385)
E/HttpOperation( 6528): 	at kfb.a(PG:29)
E/HttpOperation( 6528): 	at ixd.a(PG:248)
E/HttpOperation( 6528): 	at ixd.b(PG:206)
E/HttpOperation( 6528): 	at ixd.a(PG:175)
E/HttpOperation( 6528): 	at fig.a(PG:78)
E/HttpOperation( 6528): 	at lex.a(PG:85)
E/HttpOperation( 6528): 	at lex.b(PG:132)
E/HttpOperation( 6528): 	at fhk.a(PG:1146)
E/HttpOperation( 6528): 	at fhk.a(PG:908)
E/HttpOperation( 6528): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6528): 	at ihi.a(PG:22)
E/HttpOperation( 6528): 	at kft.a(PG:91)
E/HttpOperation( 6528): 	at kfv.a(PG:62)
E/HttpOperation( 6528): 	... 12 more
E/HttpOperation( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6528): 	at gde.c(Unknown Source)
E/HttpOperation( 6528): 	at gde.b(Unknown Source)
E/HttpOperation( 6528): 	at ihi.a(PG:19)
E/HttpOperation( 6528): 	... 14 more
,E/EsSyncAdapterService( 6528): Sync failure
E/EsSyncAdapterService( 6528): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6528): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6528): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6528): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6528): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6528): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6528): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6528): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6528): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6528): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6528): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6528): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6528): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6528): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6528): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6528): 	... 10 more
E/EsSyncAdapterService( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6528): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6528): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6528): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6528): 	... 12 more
E/EsSyncAdapterService( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6528): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6528): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6528): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6528): 	... 14 more
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  891): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 182514, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  891): mCursor = null
,E/SMD     (  284): DCD ON
,E/SQLiteLog( 1658): (10) POSIX Error : 11 SQLite Error : 3850
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 310, PST = 333, CUR = 300
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,E/Watchdog(  891): !@Sync 6
,E/SMD     (  284): DCD ON
,V/AlarmManager(  891): waitForAlarm result :8
,E/SMD     (  284): DCD ON
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  891): SIOP:: AP = 300, PST = 323, CUR = 300
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 75s ago
,E/SMD     (  284): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:m  (  891): SIOP:: AP = 300, PST = 316, CUR = 300
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  284): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  341): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  341): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 300, PST = 312, CUR = 300
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,E/Watchdog(  891): !@Sync 7
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 307, CUR = 300
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 105s ago
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  284): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 303, CUR = 300
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7311): Starting books sync, d
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1658): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1658): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1658): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1658): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1658): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1658): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1658): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1658): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7311): Authentication error
E/BooksAccountManager( 7311): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7311): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7311): null auth token
,I/qtaguid ( 7311): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7311, getuid(): 10082
,I/qtaguid ( 7311): Untagging socket 34
,W/ApiaryClient( 7311): Error response from books API: {
W/ApiaryClient( 7311):  "error": {
W/ApiaryClient( 7311):   "errors": [
W/ApiaryClient( 7311):    {
W/ApiaryClient( 7311):     "domain": "global",
W/ApiaryClient( 7311):     "reason": "required",
W/ApiaryClient( 7311):     "message": "Login Required",
W/ApiaryClient( 7311):     "locationType": "header",
W/ApiaryClient( 7311):     "location": "Authorization"
W/ApiaryClient( 7311):    }
W/ApiaryClient( 7311):   ],
W/ApiaryClient( 7311):   "code": 401,
W/ApiaryClient( 7311):   "message": "Login Required"
W/ApiaryClient( 7311):  }
W/ApiaryClient( 7311): }
,W/ApiaryClient( 7311): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7311): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7329741416566422355&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7311): Headers suppressed
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  284): DCD ON
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
,D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1658): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1658): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1658): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1658): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1658): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1658): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1658): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7311): Authentication error
E/BooksAccountManager( 7311): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7311): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7311): null auth token
,I/qtaguid ( 7311): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7311, getuid(): 10082
,I/qtaguid ( 7311): Untagging socket 34
,W/ApiaryClient( 7311): Error response from books API: {
W/ApiaryClient( 7311):  "error": {
W/ApiaryClient( 7311):   "errors": [
W/ApiaryClient( 7311):    {
W/ApiaryClient( 7311):     "domain": "global",
W/ApiaryClient( 7311):     "reason": "required",
W/ApiaryClient( 7311):     "message": "Login Required",
W/ApiaryClient( 7311):     "locationType": "header",
W/ApiaryClient( 7311):     "location": "Authorization"
W/ApiaryClient( 7311):    }
W/ApiaryClient( 7311):   ],
W/ApiaryClient( 7311):   "code": 401,
W/ApiaryClient( 7311):   "message": "Login Required"
W/ApiaryClient( 7311):  }
W/ApiaryClient( 7311): }
,W/ApiaryClient( 7311): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7311): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7329741416566422355&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7311): Headers suppressed
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1168): Icon Only
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,W/GLSActivity( 1658): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1658): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1658): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1658): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1658): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1658): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1658): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7311): Authentication error
E/BooksAccountManager( 7311): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7311): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7311): null auth token
,I/qtaguid ( 7311): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7311, getuid(): 10082
,I/qtaguid ( 7311): Untagging socket 34
,W/ApiaryClient( 7311): Error response from books API: {
W/ApiaryClient( 7311):  "error": {
W/ApiaryClient( 7311):   "errors": [
W/ApiaryClient( 7311):    {
W/ApiaryClient( 7311):     "domain": "global",
W/ApiaryClient( 7311):     "reason": "required",
W/ApiaryClient( 7311):     "message": "Login Required",
W/ApiaryClient( 7311):     "locationType": "header",
W/ApiaryClient( 7311):     "location": "Authorization"
W/ApiaryClient( 7311):    }
W/ApiaryClient( 7311):   ],
W/ApiaryClient( 7311):   "code": 401,
W/ApiaryClient( 7311):   "message": "Login Required"
W/ApiaryClient( 7311):  }
W/ApiaryClient( 7311): }
,W/ApiaryClient( 7311): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7311): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7329741416566422355&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7311): Headers suppressed
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  284): DCD ON
,E/BooksSync( 7311): Soft error
E/BooksSync( 7311): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7311): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7329741416566422355&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7311): Headers suppressed
E/BooksSync( 7311): 
E/BooksSync( 7311): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7311): Sync error
E/BooksSync( 7311): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7311): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7329741416566422355&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7311): Headers suppressed
E/BooksSync( 7311): 
E/BooksSync( 7311): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7311): Finished books sync
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  891): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 218595, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  891): mCursor = null
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  284): DCD ON,
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 300, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  284): DCD ON
,E/Watchdog(  891): !@Sync 8
,E/SMD     (  284): DCD ON
,V/AlarmManager(  891): waitForAlarm result :8
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 298, CUR = 300
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/PowerManagerService(  891): [PWL] Off : 140s ago
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,V/AlarmManager(  891): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1168): handleTimeUpdate
,D/KeyguardEffectViewController( 1168): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1168): *** don't update sliding image ***
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1168): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 296, CUR = 300
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6528): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6528): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6528): 	at kfv.a(PG:65)
E/HttpOperation( 6528): 	at kff.u(PG:385)
E/HttpOperation( 6528): 	at kfb.a(PG:29)
E/HttpOperation( 6528): 	at kff.l(PG:132)
E/HttpOperation( 6528): 	at dsf.a(PG:807)
E/HttpOperation( 6528): 	at fhk.a(PG:1126)
E/HttpOperation( 6528): 	at fhk.a(PG:908)
E/HttpOperation( 6528): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6528): 	at ihi.a(PG:22)
E/HttpOperation( 6528): 	at kft.a(PG:91)
E/HttpOperation( 6528): 	at kfv.a(PG:62)
E/HttpOperation( 6528): 	... 8 more
E/HttpOperation( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6528): 	at gde.c(Unknown Source)
E/HttpOperation( 6528): 	at gde.b(Unknown Source)
E/HttpOperation( 6528): 	at ihi.a(PG:19)
E/HttpOperation( 6528): 	... 10 more
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  284): DCD ON
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6528): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6528): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6528): 	at kfv.a(PG:65)
E/HttpOperation( 6528): 	at kff.u(PG:385)
E/HttpOperation( 6528): 	at kfb.a(PG:29)
E/HttpOperation( 6528): 	at kff.l(PG:132)
E/HttpOperation( 6528): 	at ieo.a(PG:43)
E/HttpOperation( 6528): 	at iep.a(PG:93)
E/HttpOperation( 6528): 	at fhn.a(PG:59)
E/HttpOperation( 6528): 	at lex.a(PG:85)
E/HttpOperation( 6528): 	at lex.b(PG:132)
E/HttpOperation( 6528): 	at fhk.a(PG:1146)
E/HttpOperation( 6528): 	at fhk.a(PG:908)
E/HttpOperation( 6528): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6528): 	at ihi.a(PG:22)
E/HttpOperation( 6528): 	at kft.a(PG:91)
E/HttpOperation( 6528): 	at kfv.a(PG:62)
E/HttpOperation( 6528): 	... 12 more
E/HttpOperation( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6528): 	at gde.c(Unknown Source)
E/HttpOperation( 6528): 	at gde.b(Unknown Source)
E/HttpOperation( 6528): 	at ihi.a(PG:19)
E/HttpOperation( 6528): 	... 14 more
,E/ExperimentLoader( 6528): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6528): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6528): 	at kfv.a(PG:65)
E/ExperimentLoader( 6528): 	at kff.u(PG:385)
E/ExperimentLoader( 6528): 	at kfb.a(PG:29)
E/ExperimentLoader( 6528): 	at kff.l(PG:132)
E/ExperimentLoader( 6528): 	at ieo.a(PG:43)
E/ExperimentLoader( 6528): 	at iep.a(PG:93)
E/ExperimentLoader( 6528): 	at fhn.a(PG:59)
E/ExperimentLoader( 6528): 	at lex.a(PG:85)
E/ExperimentLoader( 6528): 	at lex.b(PG:132)
E/ExperimentLoader( 6528): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6528): 	at fhk.a(PG:908)
E/ExperimentLoader( 6528): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6528): 	at ihi.a(PG:22)
E/ExperimentLoader( 6528): 	at kft.a(PG:91)
E/ExperimentLoader( 6528): 	at kfv.a(PG:62)
E/ExperimentLoader( 6528): 	... 12 more
E/ExperimentLoader( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6528): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6528): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6528): 	at ihi.a(PG:19)
E/ExperimentLoader( 6528): 	... 14 more
I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1658): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1168): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6528): [getaccountstatus] Unexpected exception
E/HttpOperation( 6528): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6528): 	at kfv.a(PG:65)
E/HttpOperation( 6528): 	at kff.u(PG:385)
E/HttpOperation( 6528): 	at kfb.a(PG:29)
E/HttpOperation( 6528): 	at ixd.a(PG:248)
E/HttpOperation( 6528): 	at ixd.b(PG:206)
E/HttpOperation( 6528): 	at ixd.a(PG:175)
E/HttpOperation( 6528): 	at fig.a(PG:78)
E/HttpOperation( 6528): 	at lex.a(PG:85)
E/HttpOperation( 6528): 	at lex.b(PG:132)
E/HttpOperation( 6528): 	at fhk.a(PG:1146)
E/HttpOperation( 6528): 	at fhk.a(PG:908)
E/HttpOperation( 6528): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6528): 	at ihi.a(PG:22)
E/HttpOperation( 6528): 	at kft.a(PG:91)
E/HttpOperation( 6528): 	at kfv.a(PG:62)
E/HttpOperation( 6528): 	... 12 more
E/HttpOperation( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6528): 	at gde.c(Unknown Source)
E/HttpOperation( 6528): 	at gde.b(Unknown Source)
E/HttpOperation( 6528): 	at ihi.a(PG:19)
E/HttpOperation( 6528): 	... 14 more
,I/PhoneStatusBar( 1168): Icon Only
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PanelView( 1168): There is/are notification(s) 
D/PanelView( 1168): There is/are notification(s) 
,E/EsSyncAdapterService( 6528): Sync failure
E/EsSyncAdapterService( 6528): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6528): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6528): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6528): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6528): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6528): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6528): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6528): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6528): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6528): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6528): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6528): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6528): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6528): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6528): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6528): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6528): 	... 10 more
E/EsSyncAdapterService( 6528): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6528): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6528): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6528): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6528): 	... 12 more
E/EsSyncAdapterService( 6528): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6528): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6528): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6528): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6528): 	... 14 more
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  891): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 249852, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2842): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  891): mCursor = null
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SQLiteLog( 1658): (10) POSIX Error : 11 SQLite Error : 3850
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  284): DCD ON
,E/Watchdog(  891): !@Sync 9
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1168): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1168): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1168):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1168): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 293, CUR = 300
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,I/ServiceManager(  341): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  341): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  284): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 180s ago
,D/TimaService(  891): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  891): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  891): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  891): initializing...
,I/TLC_TIMA_PKM_initialize(  891): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  891): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  891): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  891): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  891): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  891): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  891): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  891): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  891): App is not loaded in QSEE
,D/QSEECOMAPI: (  891): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  891): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  891): Trustlet response is completed
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 291, CUR = 300
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,E/Watchdog(  891): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/jxcore-log( 7387): --= Surplus to requirements =--
I/jxcore-log( 7387): 
,I/jxcore-log( 7387): ****TEST TOOK:  ms ****
I/jxcore-log( 7387): 
I/jxcore-log( 7387): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7387): 
,D/AndroidRuntime( 8424): 
D/AndroidRuntime( 8424): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8424): CheckJNI is OFF
,D/AndroidRuntime( 8424): setted country_code = Germany
,D/AndroidRuntime( 8424): setted countryiso_code = DE
,D/AndroidRuntime( 8424): setted sales_code = DBT
,D/AndroidRuntime( 8424): readGMSProperty: start
D/AndroidRuntime( 8424): readGMSProperty: already setted!!
,D/AndroidRuntime( 8424): readGMSProperty: end
D/AndroidRuntime( 8424): addProductProperty: start
,E/AffinityControl( 8424): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8424): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  891): START PACKAGE DELETE: observer{795757363}
D/PackageManager(  891): pkg{<packageName>}
D/PackageManager(  891): user{0}
D/PackageManager(  891): caller{2000}
D/PackageManager(  891): flags{3}
,D/PersonaManagerService(  891): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  891): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  891): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager(  891): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  891): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  891): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  891): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  891): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  891): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  891): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  891): !@killApplicatoin: 10200, uninstall pkg
,I/ActivityManager(  891): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
,I/ActivityManager(  891): Killing 7387:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
,I/ActivityManager(  891):   Force finishing activity ActivityRecord{9b3000b u0 com.test.thalitest/.MainActivity t18}
,D/FocusedStackFrame(  891): Set to : 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,E/SMD     (  284): DCD ON
,D/WifiService(  891): Client connection lost with reason: 4
,I/ActivityManager(  891): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1570): Explicit concurrent mark sweep GC freed 54779(3MB) AllocSpace objects, 0(0B) LOS objects, 39% free, 16MB/27MB, paused 619us total 44.113ms
,E/libprocessgroup(  891): failed to kill 1 processes for processgroup 7387
,I/art     ( 4579): Explicit concurrent mark sweep GC freed 5023(278KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 645us total 59.542ms
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1850): mOCRHelper is null
,W/GeofencerStateMachine( 2197): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.4.503: ( 7584): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager( 2842): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/KLMS-2.4.503: ( 7584): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1453981797732
,I/KLMS-2.4.503: ( 7584): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7584): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,I/art     (  891): Explicit concurrent mark sweep GC freed 57013(3MB) AllocSpace objects, 56(1481KB) LOS objects, 29% free, 38MB/54MB, paused 2.256ms total 222.419ms
,D/ResourcesManager(  891): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/art     (  891): WaitForGcToComplete blocked for 133.790ms for cause Explicit
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2842): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  891): mCursor = null
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/RegisteredServicesCache( 1450): empty dynamic service
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,E/Zygote  ( 8452): MountEmulatedStorage()
E/Zygote  ( 8452): v2
I/libpersona( 8452): KNOX_SDCARD checking this for 10104
I/libpersona( 8452): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8452 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/EnterpriseDeviceManagerService(  891): Package has changed for user 0
,I/SELinux ( 8452): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/EnterpriseDeviceManagerService(  891): Admin package name: com.google.android.gms
,I/SELinux ( 8452): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,E/SELinux ( 8452): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  891): PackageReceiver onReceive()
I/HarmonyEASService(  891): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  891): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/TimaKeyStoreProvider( 8452): TimaSignature is unavailable
,D/ActivityThread( 8452): Added TimaKeyStore provider
,D/BackupManagerService(  891): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  891): Receieved: android.intent.action.PACKAGE_REMOVED
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  891): uID is 10200
V/EnterpriseBillingPolicy(  891): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  891): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  891): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  891): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  891): getBillingProfileForVpnEngine - end - null
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TaskPersister(  891): removeObsoleteFile: deleting file=18_task.xml
,D/TaskPersister(  891): removeObsoleteFile: deleting file=18_task_thumbnail.png
,D/ResourcesManager( 8452): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/SurfaceWidgetView( 1462): destroyHardwareResources():91868830
,V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/WindowManager(  891): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/Launcher( 1462): onRestart, Launcher: 852533696
,D/Launcher( 1462): onStart, Launcher: 852533696
D/Launcher.HomeView( 1462): onStart
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/elm:14451( 8452): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8452): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8452): MDMBridge.setEnterpriseBridge()
,D/elm:14451( 8452): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2061): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2061): [237392/6] SurfaceWidget drawing first frame
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/elm:14451( 8452): ElmAgentService : onCreate()
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7981): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 7981): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7981): onReceive() : package name is not s health. Return !!!
,D/elm:14451( 8452): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8452): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8452): MDMBridge.getInstance()
,D/elm:14451( 8452): MDMBridge.getAllLicenseInfoFromSDK()
,I/SurfaceFlinger(  249): id=19 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  891): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/StatusBarManagerService(  891): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/elm:14451( 8452): MDMBridge.getAllLicenseInfoFromSDK()
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/PCWCLIENTTRACE_PushUtil( 6765): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6765): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6765): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6765): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/elm:14451( 8452): ElmAgentService : onDestroy().
,D/InputMethodManagerService(  891): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  891): Got RemoteException sending setActive(false) notification to pid 7387 uid 10200
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,I/art     (  891): Explicit concurrent mark sweep GC freed 16591(836KB) AllocSpace objects, 3(1328KB) LOS objects, 30% free, 36MB/52MB, paused 4.997ms total 427.679ms
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,E/Zygote  ( 8476): MountEmulatedStorage()
E/Zygote  ( 8476): v2
I/libpersona( 8476): KNOX_SDCARD checking this for 10038
I/libpersona( 8476): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8476 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 7090:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,I/SELinux ( 8476): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/SELinux ( 8476): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8476): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,I/Timeline(  891): Timeline: Activity_windows_visible id: ActivityRecord{1fa75fef u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:317429
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/PackageManager(  891): delete codoeFile: 
,W/libprocessgroup(  891): failed to open /acct/uid_10166/pid_7090/cgroup.procs: No such file or directory
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
D/TimaKeyStoreProvider( 8476): TimaSignature is unavailable
,D/PackageManager(  891): result of delete: 1{795757363}
,D/ActivityThread( 8476): Added TimaKeyStore provider
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  891): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  891): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  891): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/AndroidRuntime( 8424): Shutting down VM
,D/ResourcesManager( 8476): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,E/SPPClientService( 8476): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8476): [PushClientApplication] Push log off : This is Ship build version
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/SPPClientService( 8476): PushLog.txt file is not deleted.
D/SPPClientService( 8476): PushLog.txt file is not deleted.
D/SPPClientService( 8476): ============PushLog. stop!
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  891): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  891): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 7927): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/Zygote  ( 8492): MountEmulatedStorage()
E/Zygote  ( 8492): v2
I/libpersona( 8492): KNOX_SDCARD checking this for 10042
I/libpersona( 8492): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8492 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6604:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/SELinux ( 8492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SELinux ( 8492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,E/SELinux ( 8492): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 7927): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 8492): TimaSignature is unavailable
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ActivityThread( 8492): Added TimaKeyStore provider
,W/ResourcesManager( 7927): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/libprocessgroup(  891): failed to open /acct/uid_10012/pid_6604/cgroup.procs: No such file or directory
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 8492): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
W/ResourcesManager( 8492): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7927): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7927): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SQLiteLog( 8492): (10) unixRead() File Descriptor : 33 gets errno : 5
,E/SQLiteLog( 8492): (266) statement aborts at 15: [SELECT locale FROM android_metadata UNION SELECT NULL ORDER BY locale DESC LIMIT 1] 
,F/libc    ( 8492): Fatal signal 7 (SIGBUS), code 2, fault addr 0x757d6931 in tid 8492 (sdk.samsunglink)
,F/libc    ( 8492): Failed while talking to debuggerd: Broken pipe
,E/audit_log( 2104): File locking failed. error= Bad file number
E/audit_log( 2104): File locking failed. error= Bad file number
,I/EventHub(  891): Removing device '/dev/input/event4' due to inotify event
,I/EventHub(  891): Removing device '/dev/input/event5' due to inotify event
,I/ActivityManager(  891): Process com.samsung.android.sdk.samsunglink (pid 8492)(adj 0) has died(188,520)
,I/SA      ( 6800): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6800): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10200 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/Zygote  (  319): Process 8492 exited due to signal (7)
,F/libc    ( 2842): Fatal signal 7 (SIGBUS), code 2, fault addr 0x782317a2 in tid 2842 (ndroid.contacts)
,F/libc    ( 2842): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2104): File locking failed. error= Bad file number
,I/EventHub(  891): Removing device '/dev/input/event6' due to inotify event
,I/ActivityManager(  891): Process com.android.contacts (pid 2842)(adj 0) has died(196,521)
,F/libc    ( 1791): Fatal signal 7 (SIGBUS), code 2, fault addr 0x77e0044c in tid 1791 (d.process.acore)
F/libc    ( 1791): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2104): File locking failed. error= Bad file number
,I/Zygote  (  319): Process 2842 exited due to signal (7)
,I/EventHub(  891): Removing device '/dev/input/event7' due to inotify event
,I/ActivityManager(  891): Process android.process.acore (pid 1791)(adj 0) has died(202,521)
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/SharedPreferencesImpl( 6013): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml
,E/Zygote  ( 8519): MountEmulatedStorage()
,E/Zygote  ( 8519): v2
,I/libpersona( 8519): KNOX_SDCARD checking this for 10050
,I/libpersona( 8519): KNOX_SDCARD not a persona
,I/EventHub(  891): Removing device '/dev/input/event8' due to inotify event
,I/Zygote  (  319): Process 1791 exited due to signal (7)
,I/ActivityManager(  891): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=8519 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/art     (  319): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 482us total 18.585ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 346us total 10.836ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 345us total 10.672ms
,I/SELinux ( 8519): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
E/SELinux ( 8519): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/EventHub(  891): Removing device '/dev/input/event9' due to inotify event
,I/EventHub(  891): Removing device '/dev/input/event10' due to inotify event
,D/TimaKeyStoreProvider( 8519): TimaSignature is unavailable
,D/ActivityThread( 8519): Added TimaKeyStore provider
,D/ResourcesManager( 8519): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8519): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8519): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8519): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8519): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8519): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ContextImpl( 8519): Unable to create files subdir /data/data/com.android.mms/cache
,E/ActivityThread( 8519): Unable to setupGraphicsSupport due to missing cache directory
,I/EventHub(  891): Removing device '/dev/input/event11' due to inotify event
,D/AndroidRuntime( 8519): Shutting down VM
,F/libc    ( 8519): Fatal signal 7 (SIGBUS), code 2, fault addr 0x747306ca in tid 8519 (com.android.mms)
,F/libc    ( 8519): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2104): File locking failed. error= Bad file number
,I/ActivityManager(  891): Process com.android.mms (pid 8519)(adj 0) has died(201,521)
,I/TactileAssist(  891): enable value -1
I/TactileAssist(  891): internal enable value -1
I/TactileAssist(  891): intensity value -1
I/TactileAssist(  891): saveAppList value true
,I/TactileAssist(  891): List of disabled apps :
,I/TactileAssist(  891): de.zalando.mobile
,E/SharedPreferencesImpl(  891): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
,I/Zygote  (  319): Process 8519 exited due to signal (7)
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8534): MountEmulatedStorage()
E/Zygote  ( 8534): v2
I/libpersona( 8534): KNOX_SDCARD checking this for 10058
I/libpersona( 8534): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=8534 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,I/SELinux ( 8534): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 8534): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL

```
