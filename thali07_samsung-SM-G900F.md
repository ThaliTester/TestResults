#### Test 506502782e2cb10_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
,I/qtaguid ( 7567): Untagging socket 34
W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
W/ApiaryClient( 7567): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3092518397753737912&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
--------- beginning of system
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
E/SMD     (  282): DCD ON
I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  883): CMD_RSSI_POLL : out!
E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
D/AndroidRuntime( 7623): 
D/AndroidRuntime( 7623): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7623): CheckJNI is OFF
D/AndroidRuntime( 7623): setted country_code = Germany
D/AndroidRuntime( 7623): setted countryiso_code = DE
D/AndroidRuntime( 7623): setted sales_code = DBT
D/AndroidRuntime( 7623): readGMSProperty: start
D/AndroidRuntime( 7623): readGMSProperty: already setted!!
D/AndroidRuntime( 7623): readGMSProperty: end
D/AndroidRuntime( 7623): addProductProperty: start
E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
E/AffinityControl( 7623): AffinityControl: registerfunction enter
E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
D/AndroidRuntime( 7623): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  883): inState():  stateMachine is null !!
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  883): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
E/BooksSync( 7567): Soft error
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3092518397753737912&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7567): Headers suppressed
E/BooksSync( 7567): 
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7567): Sync error
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3092518397753737912&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7567): Headers suppressed
E/BooksSync( 7567): 
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7567): Finished books sync
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/CustomFrequencyManagerService(  883): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  883): mDVFSHelper.acquire()
I/DBG_DM  ( 3769): [com.wssyncmldm.ui.XUIInstallConfirmActivity(415/onUserLeaveHint)] 
I/SQLiteSecureOpenHelper( 3569): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3569): getDatabaseLocked(b,b,pwd)...
D/AndroidRuntime( 7623): Shutting down VM
D/SyncManager(  883): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 62843, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, Starting com.test.thalitest
I/ActivityManager(  883): Killing 6549:com.sec.chaton/u0a86 (adj 15): bgCount ##41
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/DBG_DM  ( 3769): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 39
I/DBG_DM  ( 3769): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3769): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3769): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3769): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onUserLeaveHint)] Home Key!!
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/DBG_DM  ( 3769): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
I/DBG_DM  ( 3769): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/DBG_DM  ( 3769): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/DBG_DM  ( 3769): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
D/LightsService(  883): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 883) 
D/LightsService(  883): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  883): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  883): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/PhoneStatusBar( 1167): Icon Only
W/libprocessgroup(  883): failed to open /acct/uid_10086/pid_6549/cgroup.procs: No such file or directory
I/art     (  883): Explicit concurrent mark sweep GC freed 38015(2008KB) AllocSpace objects, 15(1910KB) LOS objects, 29% free, 37MB/53MB, paused 1.304ms total 80.554ms
D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/SecContentProvider2(  883): mCursor = null
D/WindowManager(  883): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 3769): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
V/BitmapFactory( 1167): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
I/DBG_DM  ( 3769): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 3769): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
I/DBG_DM  ( 3769): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
V/BitmapFactory( 1167): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
D/KnoxNotification( 1167): ----- inflateViews : modified publicViewLocal -----
E/Zygote  ( 7646): MountEmulatedStorage()
E/Zygote  ( 7646): v2
I/libpersona( 7646): KNOX_SDCARD checking this for 10367
I/libpersona( 7646): KNOX_SDCARD not a persona
I/ActivityManager(  883): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7646 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/KnoxNotification( 1167): ----- inflateViews : modified KnoxViewLocal -----
I/SELinux ( 7646): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/PersonaManager( 1167): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1167): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@3fcc4569
I/SELinux ( 7646): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
E/SELinux ( 7646): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
D/TimaKeyStoreProvider( 7646): TimaSignature is unavailable
D/ActivityThread( 7646): Added TimaKeyStore provider
V/ActivityManager(  883): Display changed displayId=0
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/StatusBarManagerService(  883): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7646): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
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
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
I/WebViewFactory( 7646): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7646): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/LibraryLoader( 7646): Loading: webviewchromium
I/LibraryLoader( 7646): Time to load native libraries: 3 ms (timestamps 5956-5959)
I/LibraryLoader( 7646): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
V/WebViewChromiumFactoryProvider( 7646): Binding Chromium to main looper Looper (main, tid 1) {3c91c902}
I/LibraryLoader( 7646): Expected native library version number "",actual native library version number ""
I/chromium( 7646): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
I/BrowserStartupController( 7646): Initializing chromium process, renderers=0
W/art     ( 7646): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
W/chromium( 7646): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7646): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7646): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/Adreno-EGL( 7646): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7646): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7646): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7646): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7646): Remote Branch: 
I/Adreno-EGL( 7646): Local Patches: 
I/Adreno-EGL( 7646): Reconstruct Branch: 
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
W/chromium( 7646): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7646): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
W/art     ( 7646): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7646): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/SystemWebViewEngine( 7646): CordovaWebView is running on device made by: samsung
D/PowerManagerService(  883): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1167 (0x0)
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
W/art     ( 7646): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7646): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/Activity( 7646): performCreate Call secproduct feature valuefalse
D/Activity( 7646): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/OpenGLRenderer( 7646): Render dirty regions requested: true
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ActivityManager(  883): post active user change for 0
D/KnoxTimeoutHandler(  883): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  883): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
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
I/OpenGLRenderer( 7646): Initialized EGL, version 1.4
I/OpenGLRenderer( 7646): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7646): Enabling debug mode 0
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/InputMethodManagerService(  883): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/ActivityManager(  883): Displayed com.test.thalitest/.MainActivity: +624ms
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/Timeline( 7646): Timeline: Activity_idle id: android.os.BinderProxy@3e57e0bd time:96362
I/GAV2    ( 7567): Thread[GAThread,5,main]: No campaign data found.
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
D/JsMessageQueue( 7646): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/chromium( 7646): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7646): 
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/jxcore_app_log( 7646): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359596800
,D/JX-Cordova( 7646): jxcore cordova android initializing
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/9)
,I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/CustomFrequencyManagerService(  883): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  883): mDVFSHelper.release()
I/Timeline(  883): Timeline: Activity_windows_visible id: ActivityRecord{2c197ccf u0 com.test.thalitest/.MainActivity t12} time:96567
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/CustomFrequencyManagerService(  883): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  pkgName : ACTIVITY_RESUME_BOOSTER@10
I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (7/8)
,I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (-2/8)
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
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,V/AlarmManager(  883): waitForAlarm result :4
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  883): SIOP:: AP = 370, PST = 428, CUR = 300
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  883): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  tag : ACTIVITY_RESUME_BOOSTER@10
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6594): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6594): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6594): [1] 5.onFinished: Scheduling replication attempt 2.
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/SMD     (  282): DCD ON
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  883): CMD_RSSI_POLL : out!
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,W/jxcore-log( 7646): Initializing JXcore engine
,W/jxcore-log( 7646): JXcore engine is ready
,W/jxcore-log( 7646): Starting JXcore engine
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/auditd  ( 2081): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  883): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  883): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,D/SecurityLogAgent( 7482):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7482):  SeDenialReceiver : File path = null
,W/jxcore-log( 7646): Platform android
W/jxcore-log( 7646): 
,W/jxcore-log( 7646): Process ARCH arm
W/jxcore-log( 7646): 
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,V/AlarmManager(  883): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/jxcore-log( 7646): JXcore Cordova bridge is ready!
I/jxcore-log( 7646): 
,W/jxcore-log( 7646): JXcore engine is started
,E/Adreno-ES20( 7646): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7646): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/TaskPersister(  883): removeObsoleteFile: deleting file=11_task_thumbnail.png
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7646): Toggling radios to true
I/jxcore-log( 7646): 
,D/BluetoothAdapter( 7646): enable()
,D/BluetoothAdapter( 7646): enable(): BT is already enabled..!
,D/WifiService(  883): New client listening to asynchronous messages
,I/WifiManager( 7646): packageName : com.test.thalitest
,D/SecContentProvider(  883): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  883): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  883): mCursor = null
,D/WifiService(  883): setWifiEnabled: true pid=7646, uid=10367
,E/WifiService(  883): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  883): Permission Denial: getCurrentUser() from pid=7646, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  883): Failed getting userId using ActivityManagerNative
W/WifiService(  883): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7646, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  883): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  883): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  883): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  883): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  883): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  883): name = wifi_on
,I/WifiService(  883): disconnect: pid=7646, uid=10367
,I/wpa_supplicant( 1288): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7646): Radios toggled
I/jxcore-log( 7646): 
,I/jxcore-log( 7646): Got Device Bluetooth address: B0:C5:59:3F:75:69
I/jxcore-log( 7646): 
,I/jxcore-log( 7646): Perf Test app loaded loaded
I/jxcore-log( 7646): 
,I/jxcore-log( 7646): check test folder
I/jxcore-log( 7646): 
,I/jxcore-log( 7646): found test : ./testFindPeers.js
I/jxcore-log( 7646): 
,I/wpa_supplicant( 1288): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1288): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1288): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1288): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  883): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1288): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1288): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1288): Disconnected - do not scan
I/wpa_supplicant( 1288): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  883): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  883): InactiveState{ what=143375 }
,D/WifiP2pService(  883): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/jxcore-log( 7646): found test : ./testSendData.js
I/jxcore-log( 7646): 
,D/CommandListener(  276): Clearing all IP addresses on wlan0
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,V/NativeCrypto( 1673): Read error: ssl=0xaeb22200: I/O error during system call, Connection timed out
,I/jxcore-log( 7646): found test : ./testSendData2.js
I/jxcore-log( 7646): 
,V/NativeCrypto( 1673): SSL shutdown failed: ssl=0xaeb22200: I/O error during system call, Broken pipe
,E/jxcore  ( 7646): Error!: missing ) after argument list
E/jxcore  ( 7646): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,I/Choreographer( 7646): Skipped 68 frames!  The application may be doing too much work on its main thread.
,E/WifiStateMachine(  883): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
E/ConnectivityService(  883): updateNetworkInfo()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Validated
,D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  883): Validated NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  883):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  883):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  883): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  883): calling update connectivity
,I/WifiTrafficPoller(  883): evaluateTrafficStatsPolling
D/ConnectivityService(  883):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  883): Not allowed due to - mEnabled false
,D/ConnectivityService(  883):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/CLocInfoService(  883): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  883): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,D/StatusBar.NetworkController( 1167): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/ConnectivityManager.CallbackHandler( 1167): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1167): applyOpen
,I/chromium( 7646): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/WifiStateMachine(  883): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1288): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1288): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1288): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1288): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1288): First Scan Start
,E/WifiStateMachine(  883): ConnectModeState: Network connection lost 
I/wpa_supplicant( 1288): Scan requested (ret=0) - scan timeout 30 seconds
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  883): InactiveState{ what=143375 }
,D/WifiP2pService(  883): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1167): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/Hs20UtilService( 1297): Starting #6
,I/Hs20UtilService( 1297): Message received 5007
,D/NearbySettings( 1297): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1297): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1297): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/chromium( 7646): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1297): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1297): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1297): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1297): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  883): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  883): calling update connectivity
D/ConnectivityService(  883):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  883):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  883): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/PowerManagerService(  883): [s] UserActivityState : 1 -> 2
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  883): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Disconnected - quitting
D/PowerManagerService(  883): [s] DisplayPowerCallbacks : onStateChanged()
D/CommandListener(  276): Clearing all IP addresses on wlan0
,D/ConnectivityManager.CallbackHandler( 1167): CM callback handler got msg 524292
,E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService(  883): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  883): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiStateMachine(  883): updateConfiguredNetworkExpiration - currTime: 1450736041447
D/WifiStateMachine(  883): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/TelephonyNetworkFactory( 1463): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/CSLegacyTypeTracker(  883): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  883): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,I/WifiTrafficPoller(  883): evaluateTrafficStatsPolling
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  883): NetworkAgent: NetworkAgent channel lost
I/CLocInfoService(  883): External Intent Received android.net.wifi.STATE_CHANGE
D/lights  (  883): lcd : 3 +
,D/lights  (  883): lcd : 3 -
,D/StatusBar.NetworkController( 1167): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  883): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  883): mCursor = null
,D/ConnectivityService(  883): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  883): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
D/lights  (  883): lcd : 1 +
D/SmartBondingService(  883): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  883): getSBEnabled() enabled =false
D/SmartBondingService(  883): getSBEnabled() enabled =false
D/SmartBondingService(  883): getSBEnabled() enabled =false
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1167): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1167): updateDataNetType()
D/StatusBar.NetworkController( 1167): NoService, mRoamingIconId = 0
,V/NetworkStats(  883): updateIfacesLocked()
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
V/NetworkStats(  883): performPollLocked(flags=0x1)
,D/lights  (  883): lcd : 1 -
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
D/SmartBondingService(  883): getNetworkEnabled : wifi : true mobile : true
D/NetworkStatsFactory(  883): UpdateStatsForKnox
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ConnectivityService(  883): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/Hs20UtilService( 1297): Starting #7
,D/NtpTrustedTime(  883): currentTimeMillis() cache hit
,V/NetworkStats(  883): performPollLocked() took 12ms
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,I/Hs20UtilService( 1297): Message received 5007
,D/NtpTrustedTime(  883): currentTimeMillis() cache hit
,V/NetworkStats(  883): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
,D/SecContentProvider2(  883): uri = 20 selection = getPromptCredentialsEnabled
D/StatusBar.NetworkController( 1167): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/SecContentProvider2(  883): mCursor = null
,D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1167): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/NtpTrustedTime(  883): currentTimeMillis() cache hit
,D/NtpTrustedTime(  883): currentTimeMillis() cache hit
,D/NearbySettings( 1297): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1297): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1297): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1297): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1297): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1297): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1297): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1463): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1463): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1463): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1463): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1463): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1463): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1463): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1463): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1463): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1463): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1463): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1463): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1463): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1463): FileWriteThread : threadType = 3
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  883): updateDataUsageMap
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2227): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/SmartBondingService(  883): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  883): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  883): getSBEnabled() enabled =false
,D/SmartBondingService(  883): getSBEnabled() enabled =false
D/SmartBondingService(  883): getSBEnabled() enabled =false
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  883): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  883): CLoinfo wifi false
,D/SmartBondingService(  883): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3769): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7096): [#DCM#] [DCM_Performance] onReceive completed in time  260 microsec. 
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,I/NetworkMonitor( 7062): type=WIFI subType= reason=null isConnected=false
,W/SLocation(  883): No Active Data Connection
,I/DBG_DM  ( 3769): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/SystemBroadcastReceiver( 7096): [#DCM#] Calling notifyListeners. 
I/libpersona( 7753): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7753): MountEmulatedStorage()
I/libpersona( 7753): KNOX_SDCARD not a persona
E/Zygote  ( 7753): v2
I/DCMController( 7096): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7096): [#DCM#] setIsConnectedForExtractors 
,I/ActivityManager(  883): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7753 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,I/SELinux ( 7753): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7753): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7753): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7753): TimaSignature is unavailable
,D/ActivityThread( 7753): Added TimaKeyStore provider
,D/ResourcesManager( 7753): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 7753): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7753): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7753): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 7753): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7753): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7753): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7753): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7753): noConnectivity : true
,V/AlarmManager(  883): waitForAlarm result :4
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7769): MountEmulatedStorage()
E/Zygote  ( 7769): v2
I/libpersona( 7769): KNOX_SDCARD checking this for 10002
I/libpersona( 7769): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7769 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6802:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,I/SELinux ( 7769): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7769): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7769): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  883): failed to open /acct/uid_10098/pid_6802/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7769): TimaSignature is unavailable
,D/ActivityThread( 7769): Added TimaKeyStore provider
,D/ResourcesManager( 7769): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,I/ActivityManager(  883): Killing 6861:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7787): MountEmulatedStorage()
I/libpersona( 7787): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7787): v2
I/libpersona( 7787): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7787 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7787): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7787): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7787): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7787): TimaSignature is unavailable
,D/ActivityThread( 7787): Added TimaKeyStore provider
,W/libprocessgroup(  883): failed to open /acct/uid_10033/pid_6861/cgroup.procs: No such file or directory
,D/ResourcesManager( 7787): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7787): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7787): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,I/DIAGMON_AGENT( 7787): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7787): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7787): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7787): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/wpa_supplicant( 1288): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 1288): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1288): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1288): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1288): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  883): [1,450,736,042,484 ms] noteScanEnd no scan source
,E/WifiStateMachine(  883): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@7f57912 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info0x
,D/SecContentProvider2(  883): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  883): mCursor = null
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4315, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,I/CLocInfoService(  883): External Intent Received android.net.wifi.SCAN_RESULTS
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  883): Plugged
I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,I/FOTA_Client( 7301): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/FOTA_Client( 7301): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,I/wpa_supplicant( 1288): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1288): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1288): Associated with C0.AA.48
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,I/FOTA_Client( 7301): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7301): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,D/SecContentProvider2(  883): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  883): mCursor = null
,I/FOTA_Client( 7301): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7317): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7317): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450736042588
,I/wpa_supplicant( 1288): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/KLMS-2.4.503: ( 7317): MainReciver(): NETWORK_STATE_CHANGED_ACTION
I/wpa_supplicant( 1288): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info"NG700"
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  883): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  883): mCursor = null
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7317): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7317): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  883): Killing 6831:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,I/wpa_supplicant( 1288): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1288): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1288): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1288): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1288): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1288): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 1288): Blacklist: Clear (temp) 
,I/wpa_supplicant( 1288): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/SecContentProvider2(  883): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  883): mCursor = null
,E/WifiStateMachine(  883): Network connection established
,D/WifiNative-HAL(  883): callSECApiVoid - ID [50]
,E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SO_AGENT( 7333): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/WifiStateMachine(  883): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  883): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1167): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  883): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  883): Got NetworkAgent Messenger
D/ConnectivityService(  883): hsengiv:checkWhatTypeOfNetwork and the value is false
E/WifiStateMachine(  883): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/ConnectivityService(  883): updateNetworkInfo()
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  883): NetworkAgent connected
,E/Zygote  ( 7813): MountEmulatedStorage()
E/Zygote  ( 7813): v2
I/libpersona( 7813): KNOX_SDCARD checking this for 1000
I/libpersona( 7813): KNOX_SDCARD not a persona
,E/WifiStateMachine(  883): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  883): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/ActivityManager(  883): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7813 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7813): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7813): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7813): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CommandListener(  276): Setting iface cfg
,E/WifiStateMachine(  883): Start Dhcp Watchdog 2
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  883): calculateWifiScore() report new score 60
I/WifiStateMachine(  883): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  883): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  883): CMD_RSSI_POLL : out!
,D/ConnectivityService(  883): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  883): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,W/libprocessgroup(  883): failed to open /acct/uid_10099/pid_6831/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7813): TimaSignature is unavailable
,D/ActivityThread( 7813): Added TimaKeyStore provider
,D/ResourcesManager( 7813): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  883): do suspend false
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/SecContentProvider2(  883): uri = 20 selection = getPromptCredentialsEnabled
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/SecContentProvider2(  883): mCursor = null
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,D/WifiP2pService(  883): InactiveState{ what=143375 }
,D/WifiP2pService(  883): P2pEnabledState{ what=143375 }
,E/Zygote  ( 7835): MountEmulatedStorage()
E/Zygote  ( 7835): v2
I/libpersona( 7835): KNOX_SDCARD checking this for 10038
I/libpersona( 7835): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7835 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6894:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,I/art     (  310): Explicit concurrent mark sweep GC freed 8743(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 291us total 12.242ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 254us total 8.480ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.628ms
,I/SELinux ( 7835): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7835): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7835): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  883): failed to open /acct/uid_10003/pid_6894/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7835): TimaSignature is unavailable
,D/ActivityThread( 7835): Added TimaKeyStore provider
,D/ResourcesManager( 7835): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 7835): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7835): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7835): PushLog.txt file is not deleted.
,D/SPPClientService( 7835): PushLog.txt file is not deleted.
D/SPPClientService( 7835): ============PushLog. stop!
,E/SPPClientService( 7835): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6733): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6733): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6733): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6733): [SLFUCHKMGR] constructor called
,E/SPPClientService( 7835): [[SystemStateMonitorService]] No Active Internet
,I/SA      ( 6733): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6733): [OR] == isSIMCardReady false ==
,I/SA      ( 6733): [SCU] == networkStateCheck == false
I/SA      ( 6733): [OR] onReceive END
,I/ActivityManager(  883): Killing 6909:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,D/accuweather( 7373): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7373): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7858): MountEmulatedStorage()
,E/Zygote  ( 7858): v2
I/libpersona( 7858): KNOX_SDCARD checking this for 1000
I/libpersona( 7858): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7858 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7858): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,I/SELinux ( 7858): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/SELinux ( 7858): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  883): failed to open /acct/uid_10020/pid_6909/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7858): TimaSignature is unavailable
,D/ActivityThread( 7858): Added TimaKeyStore provider
,E/dhcpcd  ( 7873): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
D/ResourcesManager( 7858): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,I/dhcpcd  ( 7873): version 5.5.6 starting
,W/ResourcesManager( 7858): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/dhcpcd  ( 7873): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/KnoxUsageLogPro( 7858): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7858): premStatus:2
,I/KnoxUsageLogPro( 7858): isEulaShown : false
,I/KnoxUsageLogPro( 7858): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7878): MountEmulatedStorage()
,E/Zygote  ( 7878): v2
I/libpersona( 7878): KNOX_SDCARD checking this for 10086
I/libpersona( 7878): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.NetStateReceiver: pid=7878 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6924:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,I/dhcpcd  ( 7873): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7873): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7873): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7873): bssid match
,I/dhcpcd  ( 7873): wlan0: rebinding lease of 192.168.1.135
,I/SELinux ( 7878): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7878): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7878): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7878): TimaSignature is unavailable
,D/ActivityThread( 7878): Added TimaKeyStore provider
,W/libprocessgroup(  883): failed to open /acct/uid_1000/pid_6924/cgroup.procs: No such file or directory
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/dhcpcd  ( 7873): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/dhcpcd  ( 7873): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  883): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,D/PushModule( 7878): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 7878): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 7878): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 7878): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 7878): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  883): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 7878): [1][a] ChatONV isn't installed.
,D/ChatON  ( 7878): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7920): MountEmulatedStorage()
E/Zygote  ( 7920): v2
I/libpersona( 7920): KNOX_SDCARD checking this for 10088
I/libpersona( 7920): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7920 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6946:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,I/SELinux ( 7920): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7920): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7920): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  883): failed to open /acct/uid_10112/pid_6946/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7920): TimaSignature is unavailable
,D/ActivityThread( 7920): Added TimaKeyStore provider
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 7920): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  883): InactiveState{ what=143375 }
D/WifiP2pService(  883): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  883): WifiStateMachine DHCP successful
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  883): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/StatusBar.NetworkController( 1167): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  883): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiStateMachine(  883): Not connected state, yet.
E/WifiStateMachine(  883): VerifyingLinkState enter
,D/WifiStateMachine(  883): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine(  883): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  883): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  883): callSECApiInt - ID [210]
,E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  883): updateNetworkInfo()
,D/ConnectivityService(  883): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  883): Adding iface wlan0 to network 503
,I/CLocInfoService(  883): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  883): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  883): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  883): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  883): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  883): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1167): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  883): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  883): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  883): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  883): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  883): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  883): updateSourceRoutes : add src route for:192.168.1.135
E/WifiStateMachine(  883): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine(  883): Now, connected state.
E/WifiStateMachine(  883): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,V/        (  276): QcRouteController
,I/WifiTrafficPoller(  883): evaluateTrafficStatsPolling
,I/CLocInfoService(  883): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  883): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/StatusBar.NetworkController( 1167): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiTrafficPoller(  883): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  883): mBoosterFLAG : 0
I/WifiTrafficPoller(  883): current booster mode : FullMode
,V/        (  276): QcRouteController
,D/WifiNative-HAL(  883): callSECApiVoid - ID [212]
,I/CLocInfoService(  883): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  883): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  883): ConnectedState Enter  mScreenOn=true scanperiod=20000
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,I/WifiStateMachine(  883): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,V/        (  276): QcRouteController
,I/ActivityManager(  883): Killing 6967:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,V/        (  276): QcRouteController
,D/Headlines( 5532): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5532): getCountryCode(): countryCode = DE
,D/Headlines( 5532): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5532): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
D/HeadlinesCardManager( 5532): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5532): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5532): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5532): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5532): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,V/        (  276): QcRouteController
,E/Zygote  ( 7953): MountEmulatedStorage()
E/Zygote  ( 7953): v2
I/libpersona( 7953): KNOX_SDCARD checking this for 10128
I/libpersona( 7953): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7953 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/        (  276): QcRouteController
,V/        (  276): QcRouteController
,V/        (  276): QcRouteController
,D/ConnectivityService(  883): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  883): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  883): calling update connectivity
E/ConnectivityService(  883): updateNetworkInfo()
D/ConnectivityService(  883): ignoring duplicate network state non-change
E/ConnectivityService(  883): updateNetworkInfo()
D/ConnectivityService(  883): ignoring duplicate network state non-change
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  883): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Connected
D/ConnectivityService(  883): calling update connectivity
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Validated
D/ConnectivityService(  883):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  883):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  883):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  883): currentScore = 0, newScore = 60
D/ConnectivityService(  883):    accepting network in place of null
D/ConnectivityService(  883): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  883): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  883): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/SELinux ( 7953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7953): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TelephonyNetworkFactory( 1463): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/ActivityManager(  883): Failed to clear dns cache for: com.samsung.android.app.headlines
D/ConnectivityService(  883): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  883): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  883): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  883): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  883): getSBEnabled() enabled =false
D/SmartBondingService(  883): getSBEnabled() enabled =false
D/SmartBondingService(  883): getSBEnabled() enabled =false
D/SmartBondingService(  883): getNetworkEnabled : wifi : true mobile : true
D/EntConnectivity(  883): Not allowed due to - mEnabled false
V/NetworkStats(  883): updateIfacesLocked()
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
V/NetworkStats(  883): performPollLocked(flags=0x1)
D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  883): calling update connectivity
D/NetworkStatsFactory(  883): UpdateStatsForKnox
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  883):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  883):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  883): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  883): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  883):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkStats(  883): performPollLocked() took 3ms
D/TimaKeyStoreProvider( 7953): TimaSignature is unavailable
D/ConnectivityManager.CallbackHandler( 1167): CM callback handler got msg 524290
D/ConnectivityService(  883):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  883): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  883): calling update connectivity
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
D/ConnectivityService(  883):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  883):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
D/ConnectivityService(  883): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
V/NetworkStats(  883): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1167): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1167): updateDataNetType()
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/StatusBar.NetworkController( 1167): NoService, mRoamingIconId = 0
D/ConnectivityManager.CallbackHandler( 1167): CM callback handler got msg 524290
D/ActivityThread( 7953): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1167): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
W/libprocessgroup(  883): failed to open /acct/uid_10118/pid_6967/cgroup.procs: No such file or directory
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1167): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1167): updateDataNetType()
D/StatusBar.NetworkController( 1167): NoService, mRoamingIconId = 0
D/StatusBar.NetworkController( 1167): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ResourcesManager( 7953): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7953): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7953): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7953): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7953): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WebViewFactory( 7953): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7953): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7953): Loading: webviewchromium
,I/LibraryLoader( 7953): Time to load native libraries: 5 ms (timestamps 2429-2434)
,I/LibraryLoader( 7953): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7953): Binding Chromium to main looper Looper (main, tid 1) {2c581e0e}
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,I/LibraryLoader( 7953): Expected native library version number "",actual native library version number ""
,I/chromium( 7953): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7953): Initializing chromium process, renderers=0
,W/art     ( 7953): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7953): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7953): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7953): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7953): Requires BLUETOOTH permission
,I/Adreno-EGL( 7953): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7953): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7953): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7953): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7953): Remote Branch: 
I/Adreno-EGL( 7953): Local Patches: 
I/Adreno-EGL( 7953): Reconstruct Branch: 
,I/NSApplication( 7953): Starting up...
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8019): MountEmulatedStorage()
,E/Zygote  ( 8019): v2
I/libpersona( 8019): KNOX_SDCARD checking this for 10138
I/libpersona( 8019): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8019 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 8019): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8019): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  883): Killing 6983:com.samsung.helphub/1000 (adj 15): bgCount ##41
,E/SELinux ( 8019): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8019): TimaSignature is unavailable
,D/ActivityThread( 8019): Added TimaKeyStore provider
,D/ResourcesManager( 8019): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/libprocessgroup(  883): failed to open /acct/uid_1000/pid_6983/cgroup.procs: No such file or directory
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,W/ResourcesManager( 8019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8019): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8019): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  883): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  883): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  883): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  883): MasterInitialState.processMessage what=3
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  883): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  883): getSBEnabled() enabled =false
D/SmartBondingService(  883): getSBEnabled() enabled =false
D/SmartBondingService(  883): getSBEnabled() enabled =false
,I/CLocInfoService(  883): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  883): getNetworkEnabled : wifi : true mobile : true
I/CLocInfoService(  883): CLocinfo wifi true 
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2145): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/accuweather( 2227): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,W/ContextImpl( 2145): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3769): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3769): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7096): [#DCM#] [DCM_Performance] onReceive completed in time  149 microsec. 
,I/SystemBroadcastReceiver( 7096): [#DCM#] Calling notifyListeners. 
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DCMController( 7096): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,I/DCMController( 7096): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7062): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  883): mCursor = null
,I/DatabaseRebuilderTask( 7096): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FrameworkService( 7096): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7096): [#DCM#] onCreate FrameworkService end 
I/DCMConfig( 7096): [#DCM#] getSuccessState = true
I/FrameworkService( 7096): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
I/IntentHandler( 7096): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,D/QuickConnect( 8019): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8019): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8019): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,I/SystemUtils( 7096): [#DCM#] LM: false,AM:650334208
,E/Zygote  ( 8043): MountEmulatedStorage()
,E/Zygote  ( 8043): v2
I/libpersona( 8043): KNOX_SDCARD checking this for 10163
I/libpersona( 8043): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8043 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/DCMThreadPoolExecutor( 7096): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7096): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@1b1f062 is submitted
I/FrameworkService( 7096): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 28413 mirosec. 
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,I/SELinux ( 8043): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/DatabaseRebuilderTask( 7096): [#DCM#] createLuceneReader done 
I/DatabaseRebuilderTask( 7096): [#DCM#] resyncLocation   
I/SELinux ( 8043): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/DatabaseRebuilderTask( 7096): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
,E/SELinux ( 8043): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DatabaseRebuilderTask( 7096): [#DCM#] topDocs hits = 0
I/DatabaseRebuilderTask( 7096): [#DCM#] No of Location data to be added:  0
,D/TimaKeyStoreProvider( 8043): TimaSignature is unavailable
I/DatabaseRebuilderTask( 7096): [#DCM#] releaseLuceneReader done 
I/DatabaseRebuilderTask( 7096): [#DCM#] Starting media manager do operation 
I/SystemUtils( 7096): [#DCM#] setHeavySharedPref set as  false
,D/ActivityThread( 8043): Added TimaKeyStore provider
,I/IntentHandler( 7096): [#DCM#] Stopping service with ids up to  1
,I/ActivityManager(  883): Killing 7019:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,D/ResourcesManager( 8043): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8043): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/DCMThreadPoolExecutor( 7096): [#DCM#] afterExecute FutureTask
,W/ResourcesManager( 8043): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8043): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8043): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/DCMController( 7096): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@1b1f062
,W/libprocessgroup(  883): failed to open /acct/uid_10166/pid_7019/cgroup.procs: No such file or directory
,D/RCPManagerService(  883): exchangeData() failure , invalid userId
,D/RCPManagerService(  883): exchangeData() failure , invalid userId
,D/RCPManagerService(  883): exchangeData() failure , invalid userId
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,D/RCPManagerService(  883): exchangeData() failure , invalid userId
V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,E/Zygote  ( 8068): MountEmulatedStorage()
I/libpersona( 8068): KNOX_SDCARD checking this for 10078
E/Zygote  ( 8068): v2
I/libpersona( 8068): KNOX_SDCARD not a persona
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,I/ActivityManager(  883): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8068 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,I/SELinux ( 8068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 8068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/RCPManagerService(  883): exchangeData() failure , invalid userId
E/SELinux ( 8068): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/RCPManagerService(  883): exchangeData() failure , invalid userId
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SecurityLogAgent( 7482): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7482): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7482): StateMachine : Current State = 1
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7482): StateMachine : Changed Current State = 1
,I/ActivityManager(  883): Killing 6628:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 8068): TimaSignature is unavailable
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/ActivityThread( 8068): Added TimaKeyStore provider
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,I/ActivityManager(  883): Killing 7040:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,D/com.peel.receiver.ConnectivityActionReceiver( 5635): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 5635): 
D/com.peel.receiver.ConnectivityActionReceiver( 5635): 
D/com.peel.receiver.ConnectivityActionReceiver( 5635): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5635): 
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 5635): 
D/com.peel.receiver.ConnectivityActionReceiver( 5635): 
D/com.peel.receiver.ConnectivityActionReceiver( 5635):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5635): 
D/com.peel.receiver.ConnectivityActionReceiver( 5635): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5635): 
D/com.peel.receiver.ConnectivityActionReceiver( 5635): 
D/com.peel.receiver.ConnectivityActionReceiver( 5635): last run: 1450735958964 -- System.currentTimeMillis()-last_run: 85491
D/com.peel.receiver.ConnectivityActionReceiver( 5635): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5635): ... skip last_72_check
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 8043): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/ConnectivityService(  883): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,I/art     (  883): Explicit concurrent mark sweep GC freed 67728(3MB) AllocSpace objects, 6(96KB) LOS objects, 29% free, 37MB/53MB, paused 1.349ms total 113.234ms
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 8068): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,E/Zygote  ( 8091): MountEmulatedStorage()
E/Zygote  ( 8091): v2
I/libpersona( 8091): KNOX_SDCARD checking this for 10178
I/libpersona( 8091): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8091 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8091): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8091): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/BadgeProvider( 8068): onCreate
E/SELinux ( 8091): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/BadgeProvider( 8068): DatabaseHelper
,W/libprocessgroup(  883): failed to open /acct/uid_10170/pid_7040/cgroup.procs: No such file or directory
W/libprocessgroup(  883): failed to open /acct/uid_10012/pid_6628/cgroup.procs: No such file or directory
,D/BadgeProvider( 8068): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 8091): TimaSignature is unavailable
,D/ActivityThread( 8091): Added TimaKeyStore provider
,D/BadgeProvider( 8068): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1474): reloadBadges entered.
,D/BadgeProvider( 8068): sendNotify, [notify] : null
D/BadgeProvider( 8068): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8068): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 8068): update, [UpdateCount] : 1
,D/ResourcesManager( 8091): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  883): Killing 5709:com.sec.android.app.samsungapps/u0a40 (adj 15): bgCount ##41
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager(  883): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ChimeraCfgMgr( 2436): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2436): Loading module com.google.android.gms.kids from APK com.google.android.gms
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 8110): MountEmulatedStorage()
I/libpersona( 8110): KNOX_SDCARD checking this for 10040
E/Zygote  ( 8110): v2
I/libpersona( 8110): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=8110 uid=10040 gids={50040, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/libprocessgroup(  883): failed to open /acct/uid_10040/pid_5709/cgroup.procs: No such file or directory
I/SELinux ( 8110): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8110): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8110): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 8110): TimaSignature is unavailable
,D/ActivityThread( 8110): Added TimaKeyStore provider
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,D/ResourcesManager( 8110): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2436): [AccountUtils] Account not ready
W/Kids    ( 2436): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2436): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2436): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2436): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2436): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2436): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2436): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2436): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2436): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2436): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2436): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2436): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 8110): notifyNetworkActivated
,W/ContextImpl( 8110): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  883): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 8110): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 8110): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 8110): exit::IDLE
D/InitializeManagerStateMachine( 8110): entry::NETWORK_CHECK
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 8110): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 8110): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 8110): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 8110): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 8110): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 8110): entry::SUCCESS
D/hcjo    ( 8110): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1297): Starting #8
,I/Hs20UtilService( 1297): Message received 5007
,D/NearbySettings( 1297): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1297): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1297): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/hcjo    ( 8110): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 8110): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 8110): exit::SUCCESS
D/InitializeManagerStateMachine( 8110): entry::IDLE
I/NearbySettings( 1297): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1297): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1297): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1297): Starting #9
,I/Hs20UtilService( 1297): Message received 5007
,I/ActivityManager(  883): Killing 6203:com.google.android.gm/u0a114 (adj 15): bgCount ##41
,E/Watchdog(  883): !@Sync 3
,D/NearbySettings( 1297): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1297): MountReceiver.onReceive - Keep current state
,E/SMD     (  282): DCD ON
,I/Hs20UtilService( 1297): Starting #10
,I/Hs20UtilService( 1297): Message received 5007
,D/NearbySettings( 1297): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1297): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1297): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1297): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1297): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1297): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1297): Starting #11
,I/Hs20UtilService( 1297): Message received 5007
,D/NearbySettings( 1297): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1297): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  883): callSECApi what=220
D/WifiStateMachine(  883): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,W/libprocessgroup(  883): failed to open /acct/uid_10114/pid_6203/cgroup.procs: No such file or directory
,I/PCWCLIENTTRACE_PushUtil( 7753): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7753): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7753): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7753): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  249): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/DIAGMON_AGENT( 7787): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7787): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService(  883): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=883
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  883): [s] DisplayPowerCallbacks : onStateChanged()
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
D/lights  (  883): lcd : 8 +
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/lights  (  883): lcd : 8 -
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/FOTA_Client( 7301): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7301): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7301): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7301): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7301): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/KLMS-2.4.503: ( 7317): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7317): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450736045108
,I/KLMS-2.4.503: ( 7317): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7317): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7317): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7317): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/KLMS-2.4.503: ( 7317): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7333): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7835): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6733): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/SA      ( 6733): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 6733): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6733): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6733): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6733): [SCU] == networkStateCheck == true
,I/SA      ( 6733): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6733): isChinaCountryCode : false
I/SA      ( 6733): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6733): [OR] == networkStateCheck true ==
,I/SA      ( 6733): [OR] GetMyCountryZoneTask
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6733): [OR] onReceive END
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,I/SA      ( 6733): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1673): Connected
,I/SA      ( 6733): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6733): [SSP] query invoked
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 7373): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 7373): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6733): [TPMU] GetMccFromDB : null
,I/SA      ( 6733): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6733): [TPM] isNoProxy(default) : true
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/KnoxUsageLogPro( 7858): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7858): premStatus:2
,I/KnoxUsageLogPro( 7858): isEulaShown : false
,I/KnoxUsageLogPro( 7858): KnoxUsageReceiver onReceive : not Processible, just return
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,E/File    ( 6733): fail readDirectory() errno=2
,D/Headlines( 5532): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5532): getCountryCode(): countryCode = DE
,D/Headlines( 5532): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5532): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5532): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5532): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5532): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5532): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5532): requestUpdateNewsWelcomeCard !!! no welcome card
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1673): Message class com.google.f.a.a.p
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/QuickConnect( 8019): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8019): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8019): PeriphStartReceiver.onReceive - no need to start
E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  883): exchangeData() failure , invalid userId
,D/RCPManagerService(  883): exchangeData() failure , invalid userId
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7482): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7482): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 7482): StateMachine : Current State = 1
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/SecurityLogAgent( 7482): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5635): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5635): 
D/com.peel.receiver.ConnectivityActionReceiver( 5635): 
D/com.peel.receiver.ConnectivityActionReceiver( 5635): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5635): 
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5635): 
D/com.peel.receiver.ConnectivityActionReceiver( 5635): 
D/com.peel.receiver.ConnectivityActionReceiver( 5635):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5635): 
D/com.peel.receiver.ConnectivityActionReceiver( 5635): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5635): 
D/com.peel.receiver.ConnectivityActionReceiver( 5635): 
D/com.peel.receiver.ConnectivityActionReceiver( 5635): last run: 1450735958964 -- System.currentTimeMillis()-last_run: 86313
D/com.peel.receiver.ConnectivityActionReceiver( 5635): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5635): ... skip last_72_check
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/ChimeraCfgMgr( 2436): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2436): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/hcjo    ( 8110): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 8110): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 8110): exit::IDLE
D/InitializeManagerStateMachine( 8110): entry::NETWORK_CHECK
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 8110): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 8110): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 8110): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 8110): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 8110): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 8110): entry::SUCCESS
D/hcjo    ( 8110): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 8110): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 8110): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/InitializeManagerStateMachine( 8110): exit::SUCCESS
D/InitializeManagerStateMachine( 8110): entry::IDLE
D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GCM     ( 2436): Message from null null
E/GCM     ( 2436): Dropping message from null
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2436): [AccountUtils] Account not ready
W/Kids    ( 2436): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2436): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2436): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2436): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2436): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2436): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2436): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2436): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2436): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2436): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2436): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2436): 	at java.lang.Thread.run(Thread.java:818)
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
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
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  883): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SA      ( 6733): [RC New] Execute method=[GET] start
,I/SA      ( 6733): [RC New] Security=[true]
,I/System.out( 6733): Thread-1080(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6733): Thread-1080(ApacheHTTPLog):isShipBuild true
,I/System.out( 6733): Thread-1080(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7646): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7646): BLE supported!!
I/jxcore-log( 7646): 
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/SA      ( 6733): [RC New] [v2liruge] api execute + 700
I/SA      ( 6733): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6733): AsyncTask #1 calls detatch()
,I/SA      ( 6733): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6733): [OCP] update openData : PL
,I/SA      ( 6733): [TPMU] getNetworkMcc : 
,I/SA      ( 6733): [SCU] saveMccToPreferece Start
,I/SA      ( 6733): [SCU] RegionMCC : 260
I/SA      ( 6733): [SSP] query invoked
,I/SA      ( 6733): [TPMU] GetMccFromDB : null
I/SA      ( 6733): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6733): [SCU] saveMccToPreferece End
I/SA      ( 6733): [RC New] executeRequest [v2liruge] end. 756
I/SA      ( 6733): [RC New] Execute end
,I/SA      ( 6733): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6733): [OR] GetMyCountryZoneTask Success
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  883): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  883): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  883): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  883): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  883): identical MTU - not setting
D/ConnectivityService(  883): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  883): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
V/        (  276): QcRouteController
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService(  883): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  883): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  883): getSBEnabled() enabled =false
,D/SmartBondingService(  883): getSBEnabled() enabled =false
,D/SmartBondingService(  883): getSBEnabled() enabled =false
,V/        (  276): QcRouteController
,W/NetworkManagementService(  883): route cmd failed: 
W/NetworkManagementService(  883): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  883): '
W/NetworkManagementService(  883): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  883): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  883): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  883): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  883): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  883): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  883): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  883): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  883): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  883): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  883): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  883): calling update connectivity
,D/ConnectivityService(  883):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  883):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  883): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1167): CM callback handler got msg 524295
,D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  883): calling update connectivity
D/ConnectivityService(  883):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  883):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  883): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1167): CM callback handler got msg 524295
,I/dhcpcd  ( 7873): wlan0: sending IPv6 Router Solicitation
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  883): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  883): [PWL] On : 76060 (30001 ms ago)
I/PowerManagerService(  883): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
I/PowerManagerService(  883): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=883, ws=WorkSource{10059}) (elapsedTime=2408)
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/SMD     (  282): DCD ON
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  883): SIOP:: AP = 400, PST = 425, CUR = 300
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PowerManagerService(  883): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 883) eventTime = 107131
,D/PowerManagerService(  883): [s] UserActivityState : 4 -> 1
,D/PowerManagerService(  883): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=883 (0x0)
,D/PowerManagerService(  883): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=883, ws=WorkSource{10059}) (elapsedTime=3480)
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  883): CMD_RSSI_POLL : out!
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/GAV4    ( 7953): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
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
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,I/SurfaceFlinger(  249): id=17 Removed Toast (8/8)
,I/SurfaceFlinger(  249): id=17 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7753): mConnectivityHandler : connected
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7753): [hasSamungAccount] - No Samsung Account
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/CSTORAGE( 7753): ================================================
I/CSTORAGE( 7753):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 7753): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7753): [GetString-S]
E/art     ( 7753): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 7753): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7753): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7753): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7753): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7753): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7753): [ensureRegistration] - No Samsung account
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/SMD     (  282): DCD ON
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7873): wlan0: sending IPv6 Router Solicitation
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore in!
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  883): CMD_RSSI_POLL : out!
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/SMD     (  282): DCD ON
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  883): CMD_RSSI_POLL : out!
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 8110): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 8110): exit::IDLE
D/PreloadUpdateManagerStateMachine( 8110): entry::CHECK_TIMEOUT_FOR_UPDATE
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
D/hcjo    ( 8110): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 8110): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 8110): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 8110): entry::IDLE
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7873): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7873): wlan0: no IPv6 Routers available
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 8110): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 8110): exit::IDLE
D/PreloadUpdateManagerStateMachine( 8110): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 8110): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 8110): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 8110): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 8110): entry::IDLE
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/FactoryTest( 6444): Not factory mode
D/FactoryTest( 6444): Not factory mode. isFactoryMode() returend false
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/MTPRx   ( 6444): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6444): still no open session command from host, so toast
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness(),
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8,
,W/ContextImpl( 6444): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 ,
,I/Timeline( 6444): Timeline: Activity_launch_request id:com.android.settings time:115379,
,W/ContextImpl( 6444): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 ,
,E/PersonaManagerService(  883): inState():  stateMachine is null !!
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  883): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  883): mDVFSHelper.acquire()
,I/SQLiteSecureOpenHelper( 3569): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3569): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,E/MTPRx   ( 6444): started activity for popup
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/ResourcesManager( 6444): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6444): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6444): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6444): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6444): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6444): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6444): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6444): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6444): PREF_DONT_ASK_AGAIN : true
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
E/ActivityManager(  883): Invalid thumbnail dimensions: 576x576
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/SQLiteSecureOpenHelper( 3569): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3569): getDatabaseLocked(b,b,pwd)...
,D/InputMethodManagerService(  883): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  883): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@62bbaed attribute=null, token = android.os.BinderProxy@351de6b5
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,E/SMD     (  282): DCD ON
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6444): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6444): dev.kiessupport is : TRUE
,D/Activity( 6444): performCreate Call secproduct feature valuefalse
D/Activity( 6444): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/ActivityManager(  883): post active user change for 0
D/KnoxTimeoutHandler(  883): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  883): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/Timeline( 7646): Timeline: Activity_idle id: android.os.BinderProxy@3e57e0bd time:115642
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  883): CMD_RSSI_POLL : out!
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  883): SIOP:: AP = 360, PST = 414, CUR = 300
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,V/AlarmManager(  883): waitForAlarm result :4
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/art     ( 1673): Explicit concurrent mark sweep GC freed 30708(1860KB) AllocSpace objects, 19(1539KB) LOS objects, 40% free, 17MB/29MB, paused 716us total 44.185ms
,D/Finsky  ( 6594): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6594): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6594): [1] 5.onFinished: Scheduling replication attempt 3.
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  883): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  883): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  883): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  pkgName : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/SMD     (  282): DCD ON
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  883): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  tag : ACTIVITY_RESUME_BOOSTER@10
,I/ActivityManager(  883): Waited long enough for: ServiceRecord{3051b828 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  883): CMD_RSSI_POLL : out!
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,V/AlarmManager(  883): waitForAlarm result :4
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/SMD     (  282): DCD ON
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  883): CMD_RSSI_POLL : out!
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/SMD     (  282): DCD ON
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  883): CMD_RSSI_POLL : out!
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  883): SIOP:: AP = 340, PST = 400, CUR = 300
D/X       (  883): broadcastSiopLevelIntent:: currentSiopLevel = -1
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/ContentApp( 1218):  LEVEL : -1
,I/SystemBroadcastReceiver( 7096): [#DCM#] [DCM_Performance] onReceive completed in time  4764 microsec. 
,I/SystemBroadcastReceiver( 7096): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7096): [#DCM#] onReceive action = EVENT_SIOP
,E/Zygote  ( 8179): MountEmulatedStorage()
,E/Zygote  ( 8179): v2
I/libpersona( 8179): KNOX_SDCARD checking this for 10054
I/libpersona( 8179): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8179 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 8179): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8179): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8179): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/TimaKeyStoreProvider( 8179): TimaSignature is unavailable
,D/ActivityThread( 8179): Added TimaKeyStore provider
,D/ResourcesManager( 8179): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8179): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8179): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8179): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8179): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8179): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/TranscodeReceiver( 8179): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8179): core_num = 4
,W/linker  ( 8179): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,W/linker  ( 8179): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8179): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
D/videowall-Global( 8179): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8179):  SIOP_LEVEL: -1
,I/ActivityManager(  883): Killing 7135:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,W/libprocessgroup(  883): failed to open /acct/uid_10044/pid_7135/cgroup.procs: No such file or directory
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  883): CMD_RSSI_POLL : out!
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/SMD     (  282): DCD ON
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  883): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  883): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,D/lights  (  883): lcd : 1 +
,D/lights  (  883): lcd : 1 -
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore in!
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  883): CMD_RSSI_POLL : out!
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/Watchdog(  883): !@Sync 4
,E/SMD     (  282): DCD ON
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  883): CMD_RSSI_POLL : out!
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/SMD     (  282): DCD ON
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,D/SSRM:m  (  883): SIOP:: AP = 330, PST = 385, CUR = 300
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
,D/DisplayPowerController(  883): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  883): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  883): Nap time (uid 1000)...
I/PowerManagerService(  883): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  883): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  883): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/InputManager-JNI(  883): setDeviceInteractive: 0
,D/PowerManagerService(  883): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI(  883): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/PowerManagerService(  883): handleSandman : startDream()
,D/InputManager-JNI(  883): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,E/PowerManagerService(  883): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  883): Sleeping (uid 1000)...
D/PowerManagerService(  883): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  883): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService(  883): [input device light] handleInputDeviceLightOff
,D/InputManager-JNI(  883): sysfs_write -: /sys/class/input/event2/device/enabled: 0
I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  883): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  883): 	.unregisterCallback : 1, client=
,D/SContextService(  883): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@1853bcba, Service = Auto Rotation, used = 1
,W/CAE     (  883): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  883): stop(ContextProvider.java:149)
,V/CAE     (  883): clear(AutoRotationRunner.java:182)
,V/CAE     (  883): disable(AutoRotationRunner.java:171)
,I/CAE     (  883): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  883): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  295): sendContextData: -78, 7, 0, 0
,D/CAE     (  883): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  883): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  883): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  883): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  883): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  883): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  883): removeSContextService() : service = Auto Rotation
,D/SContextService(  883): ===== SContext Service List =====
D/SContextManager(  883):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@1b497b66, service=Auto Rotation
,D/KeyguardViewMediator( 1167): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1167): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1167): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1167): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/KeyguardViewMediator( 1167): timeout : 5000
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,I/SQLiteSecureOpenHelper( 3569): getWritableDatabase(pwd)
,D/DisplayPowerController(  883): ColorFade: onAnimationStart
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 0
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/RampAnimator(  883): mAnimationCallback timeDelta calculate error!! -0.00166338
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 0
,D/lights  (  883): lcd : 0 +
,D/DisplayPowerController(  883): getFinalBrightness : 8 -> 0
,I/SQLiteSecureOpenHelper( 3569): getDatabaseLocked(b,b,pwd)...
,D/lights  (  883): lcd : 0 -
,D/KeyguardViewMediator( 1167): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1167): handleNotifyScreenOff
,V/AlarmManager(  883): waitForAlarm result :4
,D/LightsService(  883): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 883) 
D/LightsService(  883): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  883): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  883): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  883): unregisterListener ::   
D/lights  (  883): led_pattern : 5 +
,D/BatteryService(  883): turn on LED for fully charged
,D/lights  (  883): led_pattern : 5 -
D/LightsService(  883): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  883): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  883): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  883): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
,D/SensorHubManager(  883): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  295): sendContextData: -76, 13, -46, 0
,I/CAE     (  883): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 22, 14, 38,
,D/SensorHubManager(  883): SendSensorHubData: send data = -63, 14, 22, 14, 38
D/Sensorhubs(  295): sendContextData: -63, 14, 22, 14, 38
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  883):  handler : SCREEN_OFF end 
,D/NotificationService(  883): ACTION_SCREEN_OFF
D/LightsService(  883): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 883) 
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/LightsService(  883): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 0
D/WifiStateMachine(  883): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  883): handleScreenStateChanged Exit: false
,D/LightsService(  883): [SvcLED]  onSensorChanged::light value = 0
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  883): do suspend true
,D/SensorManager(  883): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  883): unregisterListener ::   
D/LightsService(  883): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  289): adev_set_parameters: enter: screen_state=off
,V/voice   (  289): voice_set_parameters: enter: screen_state=off
V/voice   (  289): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  289): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  289): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  289): audio_extn_hfp_set_parameters: enter
,V/audio_hw_primary(  289): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  883): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  883): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  883): Bridge Server is not available
,D/VolumePanel( 1167): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1167): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1167): mCoverBroadcastReceiver: Screen OFF end
,D/VolumePanel( 1167): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  883): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  883): MSG_ACTION_SCREEN_OFF called
,D/DisplayPowerState(  883): !@ ColorFade entry
D/DisplayPowerController(  883): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  883): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  883): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  883): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,E/LightSensor(  883): Light old sensor_state 8705, new sensor_state : 8193 en : 0
D/AutomaticBrightnessController(  883): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,D/SensorManager(  883): unregisterListener ::   
,E/Sensors (  883): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
D/NfcService( 1446): call the applyRotuiing
,D/SensorManager(  883): unregisterListener ::   
,D/STATUSBAR-PhoneStatusBar( 1167):      ACTION_SCREEN_OFF is finished!!!! 
,D/DisplayPowerController(  883): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  883): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  883): Display changed displayId=0
D/DisplayPowerController(  883): getFinalBrightness : 0 -> 0
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,E/StatusBar( 1167): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1167): dismissHelpPopup 
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/accuweather( 2227): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2227): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
,D/accuweather( 2227): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/StatusBar.NetworkController( 1167): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/SystemBroadcastReceiver( 7096): [#DCM#] [DCM_Performance] onReceive completed in time  197 microsec. 
,I/SystemBroadcastReceiver( 7096): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7096): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 7096): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/SSRM:m  (  883): SIOP:: AP = 330, PST = 373, CUR = 300
,W/ActivityManager(  883): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  883): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  883): [PWL] sb release: PowerManagerService.Broadcasts
,I/rmt_storage(  269): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
,I/rmt_storage(  269): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  269): wakelock acquired: 1, error no: 42
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 22
I/rmt_storage(  269): 
,I/rmt_storage(  269): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
D/SurfaceControl(  883): Excessive delay in setPowerMode(): 254ms
D/PowerManagerService(  883): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/MISC PowerHAL(  883): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  883): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  883): Got set_interactive hint
,I/PowerManagerService(  883): [PWL] Off : 0s ago
,I/PowerManagerService(  883): [PWL]   PowerManagerService.Display: ref count=2
,I/PowerManagerService(  883): [PWL]     mDisplayReady : false
D/DisplayPowerController(  883): getFinalBrightness : 0 -> 0
,D/PowerManagerService(  883): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService(  883): [PWL] sb release: PowerManagerService.Display
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6594): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6594): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6594): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager(  883): waitForAlarm result :4
,D/KeyguardViewMediator( 1167): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1167): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/KeyguardViewMediator( 1167): doKeyguard: not showing because lockscreen is off
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,I/PowerManagerService(  883): [PWL] Off : 5s ago
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 320, PST = 364, CUR = 300,
,E/SMD     (  282): DCD ON,
,E/SMD     (  282): DCD ON
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  883): [PWL] Off : 15s ago
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :4
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  883): stay LED for fully charged
D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1673): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 5236): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at kff.l(PG:132)
E/HttpOperation( 5236): 	at dsf.a(PG:807)
E/HttpOperation( 5236): 	at fhk.a(PG:1126)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 8 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 10 more
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 5236): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at kff.l(PG:132)
E/HttpOperation( 5236): 	at ieo.a(PG:43)
E/HttpOperation( 5236): 	at iep.a(PG:93)
E/HttpOperation( 5236): 	at fhn.a(PG:59)
E/HttpOperation( 5236): 	at lex.a(PG:85)
E/HttpOperation( 5236): 	at lex.b(PG:132)
E/HttpOperation( 5236): 	at fhk.a(PG:1146)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 12 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 14 more
,E/ExperimentLoader( 5236): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5236): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5236): 	at kfv.a(PG:65)
E/ExperimentLoader( 5236): 	at kff.u(PG:385)
E/ExperimentLoader( 5236): 	at kfb.a(PG:29)
E/ExperimentLoader( 5236): 	at kff.l(PG:132)
E/ExperimentLoader( 5236): 	at ieo.a(PG:43)
E/ExperimentLoader( 5236): 	at iep.a(PG:93)
E/ExperimentLoader( 5236): 	at fhn.a(PG:59)
E/ExperimentLoader( 5236): 	at lex.a(PG:85)
E/ExperimentLoader( 5236): 	at lex.b(PG:132)
E/ExperimentLoader( 5236): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5236): 	at fhk.a(PG:908)
E/ExperimentLoader( 5236): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5236): 	at ihi.a(PG:22)
E/ExperimentLoader( 5236): 	at kft.a(PG:91)
E/ExperimentLoader( 5236): 	at kfv.a(PG:62)
E/ExperimentLoader( 5236): 	... 12 more
E/ExperimentLoader( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5236): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5236): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5236): 	at ihi.a(PG:19)
E/ExperimentLoader( 5236): 	... 14 more
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5236): [getaccountstatus] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at ixd.a(PG:248)
E/HttpOperation( 5236): 	at ixd.b(PG:206)
E/HttpOperation( 5236): 	at ixd.a(PG:175)
E/HttpOperation( 5236): 	at fig.a(PG:78)
E/HttpOperation( 5236): 	at lex.a(PG:85)
E/HttpOperation( 5236): 	at lex.b(PG:132)
E/HttpOperation( 5236): 	at fhk.a(PG:1146)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 12 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 14 more
,E/EsSyncAdapterService( 5236): Sync failure
E/EsSyncAdapterService( 5236): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5236): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5236): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5236): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5236): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5236): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5236): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5236): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5236): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5236): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5236): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5236): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5236): 	... 10 more
E/EsSyncAdapterService( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5236): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5236): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5236): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5236): 	... 12 more
E/EsSyncAdapterService( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5236): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5236): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5236): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5236): 	... 14 more
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  883): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 155258, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7567): Starting books sync, d
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  883): Explicit concurrent mark sweep GC freed 68060(3MB) AllocSpace objects, 27(3MB) LOS objects, 29% free, 37MB/53MB, paused 1.457ms total 108.197ms
,D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  883): mCursor = null
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1673): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7567): null auth token
I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
,W/ApiaryClient( 7567): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3123988874127916008&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7567): null auth token
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/qtaguid ( 7567): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,E/SMD     (  282): DCD ON
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
,W/ApiaryClient( 7567): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3123988874127916008&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  883): SIOP:: AP = 320, PST = 355, CUR = 300
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager(  883): waitForAlarm result :4
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6594): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6594): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6594): [1] 5.onFinished: Scheduling replication attempt 5.
,V/AlarmManager(  883): waitForAlarm result :8
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7567): null auth token
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
,W/ApiaryClient( 7567): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3123988874127916008&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/BooksSync( 7567): Soft error
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3123988874127916008&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7567): Headers suppressed
E/BooksSync( 7567): 
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7567): Sync error
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3123988874127916008&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7567): Headers suppressed
E/BooksSync( 7567): 
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7567): Finished books sync
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  883): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 155698, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  883): mCursor = null
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Watchdog(  883): !@Sync 5
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 310, PST = 346, CUR = 300
,I/PowerManagerService(  883): [PWL] Off : 30s ago
,E/SMD     (  282): DCD ON
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 310, PST = 339, CUR = 300
,V/AlarmManager(  883): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): stay LED for fully charged
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
I/MotionRecognitionService(  883): setPowerConnected  = true
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/VacuumService( 1673): Vacuum at: now=1450736120069 tag=VacuumService
,I/GoogleURLConnFactory( 1673): Using platform SSLCertificateSocketFactory
,W/Uploader( 1673): No account for auth token provided
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1673): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1673): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1673): (HTTPLog)-Thread-202-353867576: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1673): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1673, getuid(): 10012
,I/qtaguid ( 1673): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1673, getuid(): 10012
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6594): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6594): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6594): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1673): No account for auth token provided
,I/qtaguid ( 1673): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1673, getuid(): 10012
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1673): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1673): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1673): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1673): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1673): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1673): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1673): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1673): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1673): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1673): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
I/qtaguid ( 1673): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1673, getuid(): 10012
,W/Uploader( 1673): No account for auth token provided
,I/qtaguid ( 1673): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1673, getuid(): 10012
,W/Uploader( 1673): No account for auth token provided
,I/qtaguid ( 1673): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1673, getuid(): 10012
,W/Uploader( 1673):  no longer exists, so no auth token.
,I/qtaguid ( 1673): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1673, getuid(): 10012
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager(  883): waitForAlarm result :4
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService(  883): [PWL] Off : 50s ago
,D/SSRM:m  (  883): SIOP:: AP = 300, PST = 332, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  883): stay LED for fully charged
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  883): !@Sync 6
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 300, PST = 322, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  883): stay LED for fully charged
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 300, PST = 316, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  883): [PWL] Off : 75s ago
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :4
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7567): Starting books sync, d
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7567): null auth token
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 5236): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at kff.l(PG:132)
E/HttpOperation( 5236): 	at dsf.a(PG:807)
E/HttpOperation( 5236): 	at fhk.a(PG:1126)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 8 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 10 more
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
,W/ApiaryClient( 7567): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4520253714436836076&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 5236): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at kff.l(PG:132)
E/HttpOperation( 5236): 	at ieo.a(PG:43)
E/HttpOperation( 5236): 	at iep.a(PG:93)
E/HttpOperation( 5236): 	at fhn.a(PG:59)
E/HttpOperation( 5236): 	at lex.a(PG:85)
E/HttpOperation( 5236): 	at lex.b(PG:132)
E/HttpOperation( 5236): 	at fhk.a(PG:1146)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 12 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 14 more
,E/ExperimentLoader( 5236): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5236): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5236): 	at kfv.a(PG:65)
E/ExperimentLoader( 5236): 	at kff.u(PG:385)
E/ExperimentLoader( 5236): 	at kfb.a(PG:29)
E/ExperimentLoader( 5236): 	at kff.l(PG:132)
E/ExperimentLoader( 5236): 	at ieo.a(PG:43)
E/ExperimentLoader( 5236): 	at iep.a(PG:93)
E/ExperimentLoader( 5236): 	at fhn.a(PG:59)
E/ExperimentLoader( 5236): 	at lex.a(PG:85)
E/ExperimentLoader( 5236): 	at lex.b(PG:132)
E/ExperimentLoader( 5236): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5236): 	at fhk.a(PG:908)
E/ExperimentLoader( 5236): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5236): 	at ihi.a(PG:22)
E/ExperimentLoader( 5236): 	at kft.a(PG:91)
E/ExperimentLoader( 5236): 	at kfv.a(PG:62)
E/ExperimentLoader( 5236): 	... 12 more
E/ExperimentLoader( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5236): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5236): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5236): 	at ihi.a(PG:19)
E/ExperimentLoader( 5236): 	... 14 more
,I/art     ( 1673): Explicit concurrent mark sweep GC freed 59922(3MB) AllocSpace objects, 67(4MB) LOS objects, 40% free, 18MB/30MB, paused 921us total 87.426ms
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1673): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 5236): [getaccountstatus] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at ixd.a(PG:248)
E/HttpOperation( 5236): 	at ixd.b(PG:206)
E/HttpOperation( 5236): 	at ixd.a(PG:175)
E/HttpOperation( 5236): 	at fig.a(PG:78)
E/HttpOperation( 5236): 	at lex.a(PG:85)
E/HttpOperation( 5236): 	at lex.b(PG:132)
E/HttpOperation( 5236): 	at fhk.a(PG:1146)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 12 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 14 more
E/EsSyncAdapterService( 5236): Sync failure
E/EsSyncAdapterService( 5236): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5236): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5236): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5236): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5236): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5236): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5236): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5236): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5236): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5236): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5236): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5236): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5236): 	... 10 more
E/EsSyncAdapterService( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5236): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5236): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5236): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5236): 	... 12 more
E/EsSyncAdapterService( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5236): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5236): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5236): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5236): 	... 14 more
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  883): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 188129, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  883): mCursor = null
,I/art     (  883): Explicit concurrent mark sweep GC freed 43733(2MB) AllocSpace objects, 28(968KB) LOS objects, 29% free, 37MB/53MB, paused 1.757ms total 152.709ms
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1673): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7567): null auth token
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
,W/ApiaryClient( 7567): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4520253714436836076&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 300, PST = 312, CUR = 300
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7567): null auth token
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
,W/ApiaryClient( 7567): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4520253714436836076&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  883): waitForAlarm result :8
,E/BooksSync( 7567): Soft error
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4520253714436836076&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7567): Headers suppressed
E/BooksSync( 7567): 
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7567): Sync error
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4520253714436836076&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7567): Headers suppressed
E/BooksSync( 7567): 
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7567): Finished books sync
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  883): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 192644, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  883): mCursor = null
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/Watchdog(  883): !@Sync 7
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:m  (  883): SIOP:: AP = 300, PST = 309, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  883): SIOP:: AP = 300, PST = 306, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  883): [PWL] Off : 105s ago
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 303, CUR = 300
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,E/Watchdog(  883): !@Sync 8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 300, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 298, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  883): [PWL] Off : 140s ago
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 296, CUR = 300
,V/AlarmManager(  883): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): stay LED for fully charged
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 5236): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at kff.l(PG:132)
E/HttpOperation( 5236): 	at dsf.a(PG:807)
E/HttpOperation( 5236): 	at fhk.a(PG:1126)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 8 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 10 more
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 5236): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at kff.l(PG:132)
E/HttpOperation( 5236): 	at ieo.a(PG:43)
E/HttpOperation( 5236): 	at iep.a(PG:93)
E/HttpOperation( 5236): 	at fhn.a(PG:59)
E/HttpOperation( 5236): 	at lex.a(PG:85)
E/HttpOperation( 5236): 	at lex.b(PG:132)
E/HttpOperation( 5236): 	at fhk.a(PG:1146)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 12 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 14 more
,E/ExperimentLoader( 5236): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5236): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5236): 	at kfv.a(PG:65)
E/ExperimentLoader( 5236): 	at kff.u(PG:385)
E/ExperimentLoader( 5236): 	at kfb.a(PG:29)
E/ExperimentLoader( 5236): 	at kff.l(PG:132)
E/ExperimentLoader( 5236): 	at ieo.a(PG:43)
E/ExperimentLoader( 5236): 	at iep.a(PG:93)
E/ExperimentLoader( 5236): 	at fhn.a(PG:59)
E/ExperimentLoader( 5236): 	at lex.a(PG:85)
E/ExperimentLoader( 5236): 	at lex.b(PG:132)
E/ExperimentLoader( 5236): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5236): 	at fhk.a(PG:908)
E/ExperimentLoader( 5236): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5236): 	at ihi.a(PG:22)
E/ExperimentLoader( 5236): 	at kft.a(PG:91)
E/ExperimentLoader( 5236): 	at kfv.a(PG:62)
E/ExperimentLoader( 5236): 	... 12 more
E/ExperimentLoader( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5236): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5236): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5236): 	at ihi.a(PG:19)
E/ExperimentLoader( 5236): 	... 14 more
E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 5236): [getaccountstatus] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at ixd.a(PG:248)
E/HttpOperation( 5236): 	at ixd.b(PG:206)
E/HttpOperation( 5236): 	at ixd.a(PG:175)
E/HttpOperation( 5236): 	at fig.a(PG:78)
E/HttpOperation( 5236): 	at lex.a(PG:85)
E/HttpOperation( 5236): 	at lex.b(PG:132)
E/HttpOperation( 5236): 	at fhk.a(PG:1146)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 12 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 14 more
,E/EsSyncAdapterService( 5236): Sync failure
E/EsSyncAdapterService( 5236): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5236): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5236): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5236): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5236): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5236): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5236): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5236): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5236): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5236): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5236): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5236): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5236): 	... 10 more
E/EsSyncAdapterService( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5236): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5236): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5236): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5236): 	... 12 more
E/EsSyncAdapterService( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5236): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5236): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5236): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5236): 	... 14 more
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  883): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 280732, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  883): mCursor = null
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,E/Watchdog(  883): !@Sync 9
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,D/BatteryService(  883): stay LED for fully charged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 293, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :4
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  883): stay LED for fully charged
D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7567): Starting books sync, d
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaService(  883): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  883): TimaServiceHandler.handleMessage what =1
,D/TimaService(  883): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  883): initializing...
,I/TLC_TIMA_PKM_initialize(  883): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize(  883): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  883): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  883): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  883): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  883): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  883): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  883): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  883): App is not loaded in QSEE
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QSEECOMAPI: (  883): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  883): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/TLC_TIMA_PKM_initialize(  883): Trustlet response is completed
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7567): null auth token
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
,W/ApiaryClient( 7567): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2012319832515387474&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7567): null auth token
,I/PhoneStatusBar( 1167): Icon Only
I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
,W/ApiaryClient( 7567): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2012319832515387474&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  883): !@Sync 10
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7567): null auth token
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
,W/ApiaryClient( 7567): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2012319832515387474&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/TLC_TIMA_PKM_measure_kernel(  883): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel(  883): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  883): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  883): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/BooksSync( 7567): Soft error
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2012319832515387474&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7567): Headers suppressed
E/BooksSync( 7567): 
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7567): Sync error
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2012319832515387474&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7567): Headers suppressed
E/BooksSync( 7567): 
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7567): Finished books sync
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  883): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 284755, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  883): mCursor = null
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  883): [PWL] Off : 180s ago
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  883): waitForAlarm result :4
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8411): MountEmulatedStorage()
,I/ActivityManager(  883): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8411 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 8411): v2
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,I/libpersona( 8411): KNOX_SDCARD checking this for 10081
I/libpersona( 8411): KNOX_SDCARD not a persona
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): stay LED for fully charged
D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,I/SELinux ( 8411): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8411): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8411): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     (  310): Explicit concurrent mark sweep GC freed 8716(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 416us total 71.831ms
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 536us total 12.987ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 385us total 12.680ms
,D/TimaKeyStoreProvider( 8411): TimaSignature is unavailable
,D/ActivityThread( 8411): Added TimaKeyStore provider
,D/ResourcesManager( 8411): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  883): Killing 5953:com.sec.android.gallery3d/u0a48 (adj 15): bgCount ##41
,W/libprocessgroup(  883): failed to open /acct/uid_10048/pid_5953/cgroup.procs: No such file or directory
,E/SMD     (  282): DCD ON
,I/ActivityManager(  883): Killing 4791:com.google.android.gms.wearable/u0a12 (adj 15): bgCount ##41
,W/libprocessgroup(  883): failed to open /acct/uid_10012/pid_4791/cgroup.procs: No such file or directory
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager(  883): waitForAlarm result :8
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager(  883): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  883): !@Sync 11
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1673): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6594): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6594): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6594): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6594): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6594): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6594): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6594): 	at android.os.Binder.execTransact(Binder.java:446)
,I/art     (  883): Explicit concurrent mark sweep GC freed 48577(2MB) AllocSpace objects, 55(1465KB) LOS objects, 29% free, 37MB/53MB, paused 1.885ms total 194.350ms
,W/System  ( 6594): Ignoring header User-Agent because its value was null.
,I/System.out( 6594): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6594): (HTTPLog)-Static: isShipBuild true
I/System.out( 6594): (HTTPLog)-Thread-1063-180216038: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/PowerManagerService(  883): [PWL] Off : 225s ago
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  883): !@Sync 12
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  883): stay LED for fully charged
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :8
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 13
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager(  883): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 5236): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at kff.l(PG:132)
E/HttpOperation( 5236): 	at dsf.a(PG:807)
E/HttpOperation( 5236): 	at fhk.a(PG:1126)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 8 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 10 more
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 5236): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at kff.l(PG:132)
E/HttpOperation( 5236): 	at ieo.a(PG:43)
E/HttpOperation( 5236): 	at iep.a(PG:93)
E/HttpOperation( 5236): 	at fhn.a(PG:59)
E/HttpOperation( 5236): 	at lex.a(PG:85)
E/HttpOperation( 5236): 	at lex.b(PG:132)
E/HttpOperation( 5236): 	at fhk.a(PG:1146)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 12 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 14 more
,E/ExperimentLoader( 5236): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5236): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5236): 	at kfv.a(PG:65)
E/ExperimentLoader( 5236): 	at kff.u(PG:385)
E/ExperimentLoader( 5236): 	at kfb.a(PG:29)
E/ExperimentLoader( 5236): 	at kff.l(PG:132)
E/ExperimentLoader( 5236): 	at ieo.a(PG:43)
E/ExperimentLoader( 5236): 	at iep.a(PG:93)
E/ExperimentLoader( 5236): 	at fhn.a(PG:59)
E/ExperimentLoader( 5236): 	at lex.a(PG:85)
E/ExperimentLoader( 5236): 	at lex.b(PG:132)
E/ExperimentLoader( 5236): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5236): 	at fhk.a(PG:908)
E/ExperimentLoader( 5236): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5236): 	at ihi.a(PG:22)
E/ExperimentLoader( 5236): 	at kft.a(PG:91)
E/ExperimentLoader( 5236): 	at kfv.a(PG:62)
E/ExperimentLoader( 5236): 	... 12 more
E/ExperimentLoader( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5236): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5236): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5236): 	at ihi.a(PG:19)
E/ExperimentLoader( 5236): 	... 14 more
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
E/HttpOperation( 5236): [getaccountstatus] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at ixd.a(PG:248)
E/HttpOperation( 5236): 	at ixd.b(PG:206)
E/HttpOperation( 5236): 	at ixd.a(PG:175)
E/HttpOperation( 5236): 	at fig.a(PG:78)
E/HttpOperation( 5236): 	at lex.a(PG:85)
E/HttpOperation( 5236): 	at lex.b(PG:132)
E/HttpOperation( 5236): 	at fhk.a(PG:1146)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 12 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 14 more
,E/EsSyncAdapterService( 5236): Sync failure
E/EsSyncAdapterService( 5236): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5236): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5236): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5236): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5236): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5236): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5236): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5236): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5236): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5236): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5236): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5236): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5236): 	... 10 more
E/EsSyncAdapterService( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5236): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5236): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5236): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5236): 	... 12 more
E/EsSyncAdapterService( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5236): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5236): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5236): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5236): 	... 14 more
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  883): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 410834, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2853): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  883): mCursor = null
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService(  883): [PWL] Off : 275s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  883): !@Sync 14
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :4
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager(  883): waitForAlarm result :8
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  883): !@Sync 15
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/PowerManagerService(  883): [PWL] Off : 330s ago
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager(  883): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7567): Starting books sync, d
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7567): null auth token
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
,W/ApiaryClient( 7567): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4698866135499479859&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,I/art     ( 1673): Explicit concurrent mark sweep GC freed 40518(2MB) AllocSpace objects, 31(2MB) LOS objects, 39% free, 18MB/30MB, paused 1.023ms total 47.750ms
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1673): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7567): null auth token
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
,W/ApiaryClient( 7567): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4698866135499479859&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7567): null auth token
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
,W/ApiaryClient( 7567): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4698866135499479859&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7567): Soft error
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4698866135499479859&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7567): Headers suppressed
E/BooksSync( 7567): 
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7567): Sync error
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4698866135499479859&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7567): Headers suppressed
E/BooksSync( 7567): 
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7567): Finished books sync
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  883): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 445598, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2853): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2853): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  883): mCursor = null
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/bootchecker(  313): bootchecker wake up!!
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  883): !@Sync 16
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :4
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,D/BatteryService(  883): stay LED for fully charged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :8
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  883): !@Sync 17
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/PowerManagerService(  883): [PWL] Off : 390s ago
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  883): !@Sync 18
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Daemon(  318): Stop the daemon....
,E/Watchdog(  883): !@Sync 19
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  883): [PWL] Off : 455s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,D/BatteryService(  883): stay LED for fully charged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,D/TimaService(  883): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  883): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  883): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  883): !@Sync 20
,E/SMD     (  282): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  883): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  883): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  883): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  883): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,D/BatteryService(  883): stay LED for fully charged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  883): !@Sync 21
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  883): [PWL] Off : 525s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  883): stay LED for fully charged
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
I/MotionRecognitionService(  883): setPowerConnected  = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 1673): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
E/HttpOperation( 5236): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at kff.l(PG:132)
E/HttpOperation( 5236): 	at dsf.a(PG:807)
E/HttpOperation( 5236): 	at fhk.a(PG:1126)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 8 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 10 more
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 5236): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at kff.l(PG:132)
E/HttpOperation( 5236): 	at ieo.a(PG:43)
E/HttpOperation( 5236): 	at iep.a(PG:93)
E/HttpOperation( 5236): 	at fhn.a(PG:59)
E/HttpOperation( 5236): 	at lex.a(PG:85)
E/HttpOperation( 5236): 	at lex.b(PG:132)
E/HttpOperation( 5236): 	at fhk.a(PG:1146)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 12 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 14 more
,E/ExperimentLoader( 5236): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5236): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5236): 	at kfv.a(PG:65)
E/ExperimentLoader( 5236): 	at kff.u(PG:385)
E/ExperimentLoader( 5236): 	at kfb.a(PG:29)
E/ExperimentLoader( 5236): 	at kff.l(PG:132)
E/ExperimentLoader( 5236): 	at ieo.a(PG:43)
E/ExperimentLoader( 5236): 	at iep.a(PG:93)
E/ExperimentLoader( 5236): 	at fhn.a(PG:59)
E/ExperimentLoader( 5236): 	at lex.a(PG:85)
E/ExperimentLoader( 5236): 	at lex.b(PG:132)
E/ExperimentLoader( 5236): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5236): 	at fhk.a(PG:908)
E/ExperimentLoader( 5236): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5236): 	at ihi.a(PG:22)
E/ExperimentLoader( 5236): 	at kft.a(PG:91)
E/ExperimentLoader( 5236): 	at kfv.a(PG:62)
E/ExperimentLoader( 5236): 	... 12 more
E/ExperimentLoader( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5236): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5236): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5236): 	at ihi.a(PG:19)
E/ExperimentLoader( 5236): 	... 14 more
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5236): [getaccountstatus] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at ixd.a(PG:248)
E/HttpOperation( 5236): 	at ixd.b(PG:206)
E/HttpOperation( 5236): 	at ixd.a(PG:175)
E/HttpOperation( 5236): 	at fig.a(PG:78)
E/HttpOperation( 5236): 	at lex.a(PG:85)
E/HttpOperation( 5236): 	at lex.b(PG:132)
E/HttpOperation( 5236): 	at fhk.a(PG:1146)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 12 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 14 more
,E/EsSyncAdapterService( 5236): Sync failure
E/EsSyncAdapterService( 5236): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5236): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5236): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5236): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5236): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5236): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5236): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5236): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5236): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5236): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5236): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5236): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5236): 	... 10 more
E/EsSyncAdapterService( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5236): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5236): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5236): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5236): 	... 12 more
E/EsSyncAdapterService( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5236): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5236): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5236): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5236): 	... 14 more
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
D/SyncManager(  883): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 669716, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  883): mCursor = null
,E/SMD     (  282): DCD ON
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,E/Watchdog(  883): !@Sync 22
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,D/BatteryService(  883): stay LED for fully charged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
D/BatteryService(  883): stay LED for fully charged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :8
,V/AlarmManager(  883): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 23
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 24
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :4
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7567): Starting books sync, d
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  282): DCD ON
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7567): null auth token
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/art     ( 1167): Explicit concurrent mark sweep GC freed 73545(3MB) AllocSpace objects, 50(4MB) LOS objects, 30% free, 37MB/53MB, paused 565us total 71.579ms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
,W/ApiaryClient( 7567): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2108054411131758689&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  883): [PWL] Off : 600s ago
,I/PowerManagerService(  883): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  883): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  883): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=883, ws=WorkSource{10082}) (elapsedTime=1247)
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7567): null auth token
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/qtaguid ( 7567): Tagging socket 40 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
W/ApiaryClient( 7567): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2108054411131758689&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7567): null auth token
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,E/SMD     (  282): DCD ON
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
,W/ApiaryClient( 7567): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2108054411131758689&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/BooksSync( 7567): Soft error
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2108054411131758689&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7567): Headers suppressed
E/BooksSync( 7567): 
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7567): Sync error
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2108054411131758689&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7567): Headers suppressed
E/BooksSync( 7567): 
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7567): Finished books sync
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  883): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 736571, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  883): Explicit concurrent mark sweep GC freed 69105(4MB) AllocSpace objects, 134(2MB) LOS objects, 29% free, 37MB/53MB, paused 1.575ms total 132.516ms
D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  883): mCursor = null
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  883): !@Sync 25
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  883): !@Sync 26
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :4
,D/Finsky  ( 6594): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/LightsService(  883): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  883): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  883): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6594): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/EventLogService( 2436): Aggregate from 1450734947272 (log), 1450734947272 (data)
I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6594): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/LightSensor(  883): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  883): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  883): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  883): unregisterListener ::   
,D/LightsService(  883): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6594): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6594): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6594): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6594): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2),
,D/DeviceConnectionService( 2168): client connected with version: 7571000
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  883): [PWL] Off : 680s ago
,V/AlarmManager(  883): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  883): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6594): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6594): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6594): [1] 5.onFinished: Scheduling replication attempt 1.
,E/Watchdog(  883): !@Sync 27
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :4
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  883): stay LED for fully charged
D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6594): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6594): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6594): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON,
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  883): !@Sync 28
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :4
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  883): stay LED for fully charged
D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1673): Explicit concurrent mark sweep GC freed 36622(2MB) AllocSpace objects, 18(1458KB) LOS objects, 39% free, 18MB/30MB, paused 720us total 34.464ms
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6594): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6594): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6594): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 289, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 280, PST = 288, CUR = 300
,V/AlarmManager(  883): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog(  883): !@Sync 29
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6594): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6594): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6594): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 288, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,D/BatteryService(  883): stay LED for fully charged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 280, PST = 287, CUR = 300
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  883): [PWL] Off : 765s ago
,V/AlarmManager(  883): waitForAlarm result :4
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  883): stay LED for fully charged
D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6594): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6594): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6594): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/TimaService(  883): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  883): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  883): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 287, CUR = 300
,E/Watchdog(  883): !@Sync 30
,E/SMD     (  282): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  883): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  883): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  883): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  883): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,D/BatteryService(  883): stay LED for fully charged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 287, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :4
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6594): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6594): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6594): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 287, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 290, PST = 287, CUR = 300
,E/Watchdog(  883): !@Sync 31
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  883): stay LED for fully charged
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 280, PST = 286, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 285, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 283, CUR = 300
,E/Watchdog(  883): !@Sync 32
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 282, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 280, CUR = 300
,I/PowerManagerService(  883): [PWL] Off : 855s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 279, CUR = 300
,E/Watchdog(  883): !@Sync 33
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/GCM     ( 1673): Message class com.google.f.a.a.i
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 277, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 273, CUR = 300
,E/Watchdog(  883): !@Sync 34
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/Watchdog(  883): !@Sync 35
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  883): [PWL] Off : 950s ago
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/Watchdog(  883): !@Sync 36
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  883): stay LED for fully charged
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/Watchdog(  883): !@Sync 37
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,D/BatteryService(  883): stay LED for fully charged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/Watchdog(  883): !@Sync 38
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,D/BatteryService(  883): stay LED for fully charged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/Watchdog(  883): !@Sync 39
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): stay LED for fully charged
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
I/MotionRecognitionService(  883): setPowerConnected  = true
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1673): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5236): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at kff.l(PG:132)
E/HttpOperation( 5236): 	at dsf.a(PG:807)
E/HttpOperation( 5236): 	at fhk.a(PG:1126)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 8 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 10 more
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 5236): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at kff.l(PG:132)
E/HttpOperation( 5236): 	at ieo.a(PG:43)
E/HttpOperation( 5236): 	at iep.a(PG:93)
E/HttpOperation( 5236): 	at fhn.a(PG:59)
E/HttpOperation( 5236): 	at lex.a(PG:85)
E/HttpOperation( 5236): 	at lex.b(PG:132)
E/HttpOperation( 5236): 	at fhk.a(PG:1146)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 12 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 14 more
,E/ExperimentLoader( 5236): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5236): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5236): 	at kfv.a(PG:65)
E/ExperimentLoader( 5236): 	at kff.u(PG:385)
E/ExperimentLoader( 5236): 	at kfb.a(PG:29)
E/ExperimentLoader( 5236): 	at kff.l(PG:132)
E/ExperimentLoader( 5236): 	at ieo.a(PG:43)
E/ExperimentLoader( 5236): 	at iep.a(PG:93)
E/ExperimentLoader( 5236): 	at fhn.a(PG:59)
E/ExperimentLoader( 5236): 	at lex.a(PG:85)
E/ExperimentLoader( 5236): 	at lex.b(PG:132)
E/ExperimentLoader( 5236): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5236): 	at fhk.a(PG:908)
E/ExperimentLoader( 5236): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5236): 	at ihi.a(PG:22)
E/ExperimentLoader( 5236): 	at kft.a(PG:91)
E/ExperimentLoader( 5236): 	at kfv.a(PG:62)
E/ExperimentLoader( 5236): 	... 12 more
E/ExperimentLoader( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5236): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5236): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5236): 	at ihi.a(PG:19)
E/ExperimentLoader( 5236): 	... 14 more
,I/PowerManagerService(  883): [PWL] Off : 1050s ago
I/PowerManagerService(  883): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  883): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  883): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.plus.content.EsProvider/com.google/eM_ADDR' (uid=1000, pid=883, ws=WorkSource{10135}) (elapsedTime=433)
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 5236): [getaccountstatus] Unexpected exception
E/HttpOperation( 5236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5236): 	at kfv.a(PG:65)
E/HttpOperation( 5236): 	at kff.u(PG:385)
E/HttpOperation( 5236): 	at kfb.a(PG:29)
E/HttpOperation( 5236): 	at ixd.a(PG:248)
E/HttpOperation( 5236): 	at ixd.b(PG:206)
E/HttpOperation( 5236): 	at ixd.a(PG:175)
E/HttpOperation( 5236): 	at fig.a(PG:78)
E/HttpOperation( 5236): 	at lex.a(PG:85)
E/HttpOperation( 5236): 	at lex.b(PG:132)
E/HttpOperation( 5236): 	at fhk.a(PG:1146)
E/HttpOperation( 5236): 	at fhk.a(PG:908)
E/HttpOperation( 5236): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5236): 	at ihi.a(PG:22)
E/HttpOperation( 5236): 	at kft.a(PG:91)
E/HttpOperation( 5236): 	at kfv.a(PG:62)
E/HttpOperation( 5236): 	... 12 more
E/HttpOperation( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5236): 	at gde.c(Unknown Source)
E/HttpOperation( 5236): 	at gde.b(Unknown Source)
E/HttpOperation( 5236): 	at ihi.a(PG:19)
E/HttpOperation( 5236): 	... 14 more
,E/EsSyncAdapterService( 5236): Sync failure
E/EsSyncAdapterService( 5236): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5236): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5236): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5236): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5236): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5236): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5236): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5236): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5236): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5236): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5236): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5236): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5236): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5236): 	... 10 more
E/EsSyncAdapterService( 5236): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5236): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5236): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5236): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5236): 	... 12 more
E/EsSyncAdapterService( 5236): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5236): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5236): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5236): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5236): 	... 14 more
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  883): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1186870, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  883): Explicit concurrent mark sweep GC freed 65629(4MB) AllocSpace objects, 136(2MB) LOS objects, 29% free, 38MB/54MB, paused 1.578ms total 134.585ms
,D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  883): mCursor = null
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/TimaService(  883): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  883): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  883): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  883): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  883): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  883): Updating Usage Statistics in DB @ 1450737153200
,I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
,W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
,W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
,W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
,W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  883): ::getAppControlDB: Exception to create DB
W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  883): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  883): Done Updating Usage Statistics in DB @ 1450737153444
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/Watchdog(  883): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel(  883): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  883): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  883): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  883): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :4
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 280, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged,
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 271, CUR = 300
,E/Watchdog(  883): !@Sync 41
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  883): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 271, CUR = 300
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7567): Starting books sync, d
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1673): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7567): null auth token
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
,W/ApiaryClient( 7567): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2103438254144955962&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7567): null auth token
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/qtaguid ( 7567): Tagging socket 41 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
,W/ApiaryClient( 7567): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2103438254144955962&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7567): Authentication error
E/BooksAccountManager( 7567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7567): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7567): null auth token
,I/qtaguid ( 7567): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7567, getuid(): 10082
,I/qtaguid ( 7567): Untagging socket 34
,W/ApiaryClient( 7567): Error response from books API: {
W/ApiaryClient( 7567):  "error": {
W/ApiaryClient( 7567):   "errors": [
W/ApiaryClient( 7567):    {
W/ApiaryClient( 7567):     "domain": "global",
W/ApiaryClient( 7567):     "reason": "required",
W/ApiaryClient( 7567):     "message": "Login Required",
W/ApiaryClient( 7567):     "locationType": "header",
W/ApiaryClient( 7567):     "location": "Authorization"
W/ApiaryClient( 7567):    }
W/ApiaryClient( 7567):   ],
W/ApiaryClient( 7567):   "code": 401,
W/ApiaryClient( 7567):   "message": "Login Required"
W/ApiaryClient( 7567):  }
W/ApiaryClient( 7567): }
,W/ApiaryClient( 7567): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2103438254144955962&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7567): Headers suppressed
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7567): Soft error
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2103438254144955962&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7567): Headers suppressed
E/BooksSync( 7567): 
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7567): Sync error
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7567): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2103438254144955962&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7567): Headers suppressed
E/BooksSync( 7567): 
E/BooksSync( 7567): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7567): Finished books sync
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/SyncManager(  883): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1263396, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  883): mCursor = null
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 271, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,E/Watchdog(  883): !@Sync 42
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  883): [PWL] Off : 1155s ago
,V/AlarmManager(  883): waitForAlarm result :4
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  883): stay LED for fully charged
D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 43
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 271, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 44
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 45
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 46
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  883): [PWL] Off : 1265s ago
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,D/BatteryService(  883): stay LED for fully charged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 47
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 48
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 269, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 49
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 268, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 267, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 266, CUR = 300
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/TimaService(  883): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  883): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  883): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  883): !@Sync 50
,E/SMD     (  282): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  883): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  883): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  883): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  883): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 266, CUR = 300
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  883): [PWL] Off : 1380s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 266, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/LightsService(  883): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  883): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  883): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  883): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  883): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  883): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  883): unregisterListener ::   
,D/LightsService(  883): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 266, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,V/AlarmManager(  883): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 51
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 266, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 266, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 266, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 52
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 266, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 266, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 266, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 53
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 266, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 265, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 264, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 54
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 263, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,I/PowerManagerService(  883): [PWL] Off : 1500s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 261, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  883): stay LED for fully charged
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 55
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 56
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 57
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,E/SMD     (  282): DCD ON
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 58
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,D/BatteryService(  883): stay LED for fully charged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  883): [PWL] Off : 1625s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 59
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/NetworkStatsFactory(  883): UpdateStatsForKnox
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/TimaService(  883): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  883): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  883): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  883): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel(  883): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  883): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  883): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  883): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 261, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): stay LED for fully charged
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 270, PST = 262, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 61
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 262, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 262, CUR = 300
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/BatteryService(  883): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 62
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  883): [PWL] Off : 1755s ago
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  883): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  883): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  883): Plugged
,D/BatteryService(  883): stay LED for fully charged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/Watchdog(  883): !@Sync 63
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8803): 
D/AndroidRuntime( 8803): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8803): CheckJNI is OFF
D/AndroidRuntime( 8803): setted country_code = Germany
D/AndroidRuntime( 8803): setted countryiso_code = DE
D/AndroidRuntime( 8803): setted sales_code = DBT
D/AndroidRuntime( 8803): readGMSProperty: start
D/AndroidRuntime( 8803): readGMSProperty: already setted!!
D/AndroidRuntime( 8803): readGMSProperty: end
D/AndroidRuntime( 8803): addProductProperty: start
D/SSRM:m  (  883): SIOP:: AP = 260, PST = 262, CUR = 300
E/AffinityControl( 8803): AffinityControl: registerfunction enter
D/AndroidRuntime( 8803): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  883): START PACKAGE DELETE: observer{247207186}
D/PackageManager(  883): pkg{<packageName>}
D/PackageManager(  883): user{0}
D/PackageManager(  883): caller{2000}
D/PackageManager(  883): flags{3}
D/PersonaManagerService(  883): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  883): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  883): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  883): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  883): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  883): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  883): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  883): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  883): getApplicationUninstallationEnabled
D/ApplicationPolicy(  883): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  883): !@killApplicatoin: 10367, uninstall pkg
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
I/ActivityManager(  883): Killing 7646:com.test.thalitest/u0a367 (adj 0): stop com.test.thalitest
I/ActivityManager(  883): Killing 8019:com.samsung.android.sconnect/u0a138 (adj 15): empty for 1803s
I/ActivityManager(  883): Killing 7953:com.google.android.apps.magazines/u0a128 (adj 15): empty for 1803s
I/ActivityManager(  883): Killing 7920:com.android.chrome/u0a88 (adj 15): empty for 1803s
I/ActivityManager(  883): Killing 7878:com.sec.chaton/u0a86 (adj 15): empty for 1803s
I/ActivityManager(  883): Killing 7858:com.sec.knox.bridge/1000 (adj 15): empty for 1803s
I/ActivityManager(  883): Killing 7373:com.sec.android.widgetapp.ap.hero.accuweather/u0a71 (adj 15): empty for 1803s
I/ActivityManager(  883): Killing 6733:com.osp.app.signin/u0a45 (adj 15): empty for 1803s
I/ActivityManager(  883): Killing 7813:com.policydm/1000 (adj 15): empty for 1803s
I/ActivityManager(  883): Killing 7333:com.sec.android.soagent/u0a37 (adj 15): empty for 1803s
I/ActivityManager(  883): Killing 7317:com.samsung.klmsagent/u0a19 (adj 15): empty for 1803s
I/ActivityManager(  883): Killing 7301:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1803s
I/ActivityManager(  883): Killing 7787:com.sec.android.diagmonagent/1000 (adj 15): empty for 1803s
I/ActivityManager(  883): Killing 7769:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1804s
I/ActivityManager(  883): Killing 7062:com.google.android.music:main/u0a126 (adj 15): empty for 1804s
I/ActivityManager(  883): Killing 7753:com.sec.pcw.device/1000 (adj 15): empty for 1804s
I/ActivityManager(  883): Killing 8068:com.sec.android.provider.badge/u0a78 (adj 15): empty for 1804s
I/ActivityManager(  883): Killing 7096:com.samsung.dcm:DCMService/u0a4 (adj 15): empty for 1804s
I/ActivityManager(  883): Killing 7475:com.android.providers.calendar/u0a46 (adj 15): empty for 1823s
I/ActivityManager(  883): Killing 7455:com.android.calendar/u0a150 (adj 15): empty for 1825s
I/ActivityManager(  883): Killing 7440:com.sec.android.widgetapp.SPlannerAppWidget/u0a149 (adj 15): empty for 1825s
I/ActivityManager(  883): Killing 7523:com.qualcomm.timeservice/1000 (adj 15): empty for 1826s
I/ActivityManager(  883): Killing 7508:com.sec.android.app.taskmanager/u0a176 (adj 15): empty for 1826s
I/ActivityManager(  883): Killing 7423:com.sec.android.GeoLookout/u0a113 (adj 15): empty for 1827s
I/ActivityManager(  883): Killing 7406:com.sec.esdk.elm/u0a104 (adj 15): empty for 1827s
I/ActivityManager(  883): Killing 7390:com.sec.android.app.clockpackage/u0a91 (adj 15): empty for 1827s
I/ActivityManager(  883): Killing 7352:com.samsung.android.scloud.sync/u0a67 (adj 15): empty for 1828s
I/ActivityManager(  883): Killing 5832:com.android.mms/u0a50 (adj 15): empty for 1828s
I/ActivityManager(  883): Killing 4609:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1828s
I/ActivityManager(  883): Killing 5029:com.android.defcontainer/u0a5 (adj 15): empty for 1839s
D/WifiService(  883): Client connection lost with reason: 4
I/WindowState(  883): WIN DEATH: Window{1f04914a u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
I/ActivityManager(  883):   Force finishing activity ActivityRecord{2c197ccf u0 com.test.thalitest/.MainActivity t12}
I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/FocusedStackFrame(  883): Set to : 0
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/ProcessStatsService(  883): Prepared write state in 7ms
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/CountryDetector(  883): No listener is left
W/PackageSettings(  883): Skipping PackageSetting{750685e com.example.hello/10375} due to missing metadata
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
I/art     ( 4466): Explicit concurrent mark sweep GC freed 4026(225KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 330us total 21.367ms
I/art     ( 1569): Explicit concurrent mark sweep GC freed 34395(2040KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/27MB, paused 427us total 33.329ms
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1863): mOCRHelper is null
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
W/GeofencerStateMachine( 2168): Ignoring removeGeofence because network location is disabled.
E/Zygote  ( 8832): MountEmulatedStorage()
E/Zygote  ( 8832): v2
I/libpersona( 8832): KNOX_SDCARD checking this for 10019
I/libpersona( 8832): KNOX_SDCARD not a persona
I/ActivityManager(  883): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8832 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 8832): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8832): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8832): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ProcessStatsService(  883): Pruning old procstats: /data/system/procstats/state-2015-12-21-00-50-00.bin
I/art     (  883): Explicit concurrent mark sweep GC freed 75548(7MB) AllocSpace objects, 233(3MB) LOS objects, 29% free, 38MB/54MB, paused 1.308ms total 128.077ms
I/art     (  883): WaitForGcToComplete blocked for 67.240ms for cause Explicit
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  883): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/TimaKeyStoreProvider( 8832): TimaSignature is unavailable
D/ActivityThread( 8832): Added TimaKeyStore provider
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/SurfaceWidgetView( 1474): destroyHardwareResources():343960436
V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  883): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ResourcesManager( 8832): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/Launcher( 1474): onRestart, Launcher: 452152700
D/Launcher( 1474): onStart, Launcher: 452152700
D/Launcher.HomeView( 1474): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2227): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/SurfaceWidget.Renderer( 2227): [237392/6] SurfaceWidget drawing first frame
D/LockPatternUtilsCache( 1167): value : false
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/SurfaceFlinger(  249): id=19 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/StatusBarManagerService(  883): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/StatusBarManagerService(  883): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/RegisteredServicesCache( 1446): empty dynamic service
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  883): mCursor = null
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
I/KLMS-2.4.503: ( 8832): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
I/KLMS-2.4.503: ( 8832): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1450737849647
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/KLMS-2.4.503: ( 8832): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.503: ( 8832): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/InputMethodManagerService(  883): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  883): Got RemoteException sending setActive(false) notification to pid 7646 uid 10367
W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/EnterpriseDeviceManagerService(  883): Package has changed for user 0
D/EnterpriseDeviceManagerService(  883): Admin package name: com.google.android.gms
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
E/Zygote  ( 8854): MountEmulatedStorage()
E/Zygote  ( 8854): v2
I/libpersona( 8854): KNOX_SDCARD checking this for 10104
I/libpersona( 8854): KNOX_SDCARD not a persona
I/ActivityManager(  883): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8854 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
I/art     (  883): Explicit concurrent mark sweep GC freed 13804(670KB) AllocSpace objects, 1(64KB) LOS objects, 29% free, 38MB/54MB, paused 8.379ms total 253.663ms
I/ActivityManager(  883): Killing 8043:com.android.email/u0a163 (adj 15): empty for 1804s
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Books/Books.apk
I/SELinux ( 8854): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/SELinux ( 8854): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8854): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/Timeline(  883): Timeline: Activity_windows_visible id: ActivityRecord{77305d5 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:1908421
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/TimaKeyStoreProvider( 8854): TimaSignature is unavailable
D/ActivityThread( 8854): Added TimaKeyStore provider
D/PackageManager(  883): delete codoeFile: 
D/PackageManager(  883): result of delete: 1{247207186}
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/AndroidRuntime( 8803): Shutting down VM
D/ResourcesManager( 8854): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(  883): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/elm:14451( 8854): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8854): ELMEngine.ELMEngine( context ).
D/elm:14451( 8854): MDMBridge.setEnterpriseBridge()
D/elm:14451( 8854): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
D/elm:14451( 8854): ElmAgentService : onCreate()
D/elm:14451( 8854): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/RCPManagerService(  883): PackageReceiver onReceive()
I/HarmonyEASService(  883): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  883): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 8870): MountEmulatedStorage()
E/Zygote  ( 8870): v2
I/libpersona( 8870): KNOX_SDCARD checking this for 10017
I/libpersona( 8870): KNOX_SDCARD not a persona
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/elm:14451( 8854): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8854): MDMBridge.getInstance()
D/elm:14451( 8854): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 8870): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8870): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  883): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8870 uid=10017 gids={50017, 9997} abi=armeabi-v7a
E/SELinux ( 8870): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:14451( 8854): MDMBridge.getAllLicenseInfoFromSDK()
D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  883): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  883): uID is 10367
V/EnterpriseBillingPolicy(  883): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  883): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  883): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  883): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  883): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  883): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  883): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  883): removeObsoleteFile: deleting file=12_task.xml
D/TaskPersister(  883): removeObsoleteFile: deleting file=12_task_thumbnail.png
D/elm:14451( 8854): ElmAgentService : onDestroy().
I/ActivityManager(  883): Killing 7482:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1804s
D/TimaKeyStoreProvider( 8870): TimaSignature is unavailable
D/ActivityThread( 8870): Added TimaKeyStore provider
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 8870): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8870): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8870): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8870): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
E/Zygote  ( 8886): MountEmulatedStorage()
E/Zygote  ( 8886): v2
I/libpersona( 8886): KNOX_SDCARD checking this for 1000
I/libpersona( 8886): KNOX_SDCARD not a persona
I/SELinux ( 8886): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8886): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  883): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8886 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  883): Killing 8091:com.samsung.android.service.travel/u0a178 (adj 15): empty for 1804s
E/SELinux ( 8886): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(  883): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  883): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  883): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
D/TimaKeyStoreProvider( 8886): TimaSignature is unavailable
D/ActivityThread( 8886): Added TimaKeyStore provider
D/ResourcesManager(  883): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
D/ResourcesManager( 8886): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
D/ResourcesManager(  883): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
I/PCWCLIENTTRACE_LOG( 8886): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 8886): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 8886): new DMDBOpenHelper instance
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/PCWCLIENTTRACE_PushUtil( 8886): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 8886): sales region : global
I/PCWCLIENTTRACE_PushUtil( 8886): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 8886): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
E/Zygote  ( 8901): MountEmulatedStorage()
E/Zygote  ( 8901): v2
I/libpersona( 8901): KNOX_SDCARD checking this for 10034
I/libpersona( 8901): KNOX_SDCARD not a persona
I/ActivityManager(  883): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8901 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  883): Killing 7835:com.sec.spp.push/u0a38 (adj 15): empty for 1801s
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk

```
