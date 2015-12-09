#### Test 50650278d0426ce_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
--------- beginning of system
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  887): uri = 14 selection = getSealedState
D/SecContentProvider2(  887): mCursor = null
D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7348): null auth token
I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/qtaguid ( 7348): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
I/qtaguid ( 7348): Untagging socket 34
W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
W/ApiaryClient( 7348): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4984500897447644374&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
D/AndroidRuntime( 7401): 
D/AndroidRuntime( 7401): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7401): CheckJNI is OFF
D/AndroidRuntime( 7401): setted country_code = Germany
D/AndroidRuntime( 7401): setted countryiso_code = DE
D/AndroidRuntime( 7401): setted sales_code = DBT
D/AndroidRuntime( 7401): readGMSProperty: start
D/AndroidRuntime( 7401): readGMSProperty: already setted!!
D/AndroidRuntime( 7401): readGMSProperty: end
D/AndroidRuntime( 7401): addProductProperty: start
E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
E/SMD     (  285): DCD ON
E/AffinityControl( 7401): AffinityControl: registerfunction enter
E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
D/AndroidRuntime( 7401): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  887): inState():  stateMachine is null !!
V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  887): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  887): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  887): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 887  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  887): mDVFSHelper.acquire()
D/FocusedStackFrame(  887): Set to : 0
D/Launcher.HomeView( 1471): onPause
D/Launcher( 1471): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 7401): Shutting down VM
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/Zygote  ( 7421): MountEmulatedStorage()
E/Zygote  ( 7421): v2
I/libpersona( 7421): KNOX_SDCARD checking this for 10367
I/libpersona( 7421): KNOX_SDCARD not a persona
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/ActivityManager(  887): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7421 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7421): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
I/SELinux ( 7421): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7421): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
V/TaskCloserActivity( 7174): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
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
D/StatusBarManagerService(  887): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/TimaKeyStoreProvider( 7421): TimaSignature is unavailable
D/ActivityThread( 7421): Added TimaKeyStore provider
V/WindowOrientationListener(  887): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  887): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  887): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  887): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  887): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
I/MicrophoneInputStream( 1571): mic_close gfk@26a1815
V/ActivityManager(  887): Display changed displayId=0
D/Launcher.HomeView( 1471): onStop
V/AudioPolicyManager(  292): stopInput() input 29
V/AudioPolicyManager(  292): releaseInput() 29
V/AudioPolicyManager(  292): closeInput(29)
V/audio_hw_primary(  292): in_standby: enter
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2102): [237392/6] Surface widget pause on instance = 1
D/accuweather( 2102): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2102): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2102): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/HotwordRecognitionRnr( 1571): Stopping hotword detection.
I/HotwordRecognitionRnr( 1571): Hotword detection finished
D/SurfaceWidgetView( 1471): destroyHardwareResources():140859509
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2102): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
V/audio_hw_primary(  292): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  292): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  292): disable_audio_route: reset mixer path: audio-record
D/audio_route(  292): ++++ audio_route_update_mixer ==============
D/audio_route(  292): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  292): Setting mixer control: value: 0
E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
D/audio_route(  292): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  292): disable_audio_route: exit
V/audio_hw_primary(  292): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  292): ++++ audio_route_update_mixer ==============
D/audio_route(  292): Setting mixer control: DEC2 Volume
D/audio_route(  292): Setting mixer control: value: 0
D/audio_route(  292): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  292): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  292): Setting mixer control: value: 0
D/audio_route(  292): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  292): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  292): stop_input_stream: exit: status(0)
V/audio_hw_primary(  292): in_standby: exit:  status(0)
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2102): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2102): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
V/audio_hw_primary(  292): adev_close_input_stream
V/audio_hw_primary(  292): in_standby: enter
V/audio_hw_primary(  292): in_standby: exit:  status(0)
E/audio_hw_primary(  292): adev_close_input_stream, set jack_in to null
D/LockPatternUtilsCache( 1172): value : false
V/AudioPolicyManager(  292): releaseInput() exit
D/ResourcesManager( 7421): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/StatusBarManagerService(  887): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/Launcher( 1471): onTrimMemory. Level: 20
D/SurfaceWidgetView( 1471): destroyHardwareResources():140859509
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
I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  887): CMD_RSSI_POLL : out!
V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  887): uri = 14 selection = getSealedState
D/SecContentProvider2(  887): mCursor = null
D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7348): null auth token
I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/WebViewFactory( 7421): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7421): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/LibraryLoader( 7421): Loading: webviewchromium
I/LibraryLoader( 7421): Time to load native libraries: 2 ms (timestamps 5092-5094)
I/LibraryLoader( 7421): Expected native library version number "",actual native library version number ""
E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/qtaguid ( 7348): Untagging socket 34
W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
W/ApiaryClient( 7348): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4984500897447644374&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/WebViewChromiumFactoryProvider( 7421): Binding Chromium to main looper Looper (main, tid 1) {19c4541c}
I/LibraryLoader( 7421): Expected native library version number "",actual native library version number ""
I/chromium( 7421): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/BrowserStartupController( 7421): Initializing chromium process, renderers=0
W/art     ( 7421): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7421): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7421): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7421): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/Adreno-EGL( 7421): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7421): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7421): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7421): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7421): Remote Branch: 
I/Adreno-EGL( 7421): Local Patches: 
I/Adreno-EGL( 7421): Reconstruct Branch: 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/chromium( 7421): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7421): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7421): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7421): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/SystemWebViewEngine( 7421): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/art     ( 7421): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7421): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/Activity( 7421): performCreate Call secproduct feature valuefalse
D/Activity( 7421): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/OpenGLRenderer( 7421): Render dirty regions requested: true
D/ActivityManager(  887): post active user change for 0
D/KnoxTimeoutHandler(  887): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  887): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
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
I/OpenGLRenderer( 7421): Initialized EGL, version 1.4
I/OpenGLRenderer( 7421): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7421): Enabling debug mode 0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/InputMethodManagerService(  887): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/ActivityManager(  887): Displayed com.test.thalitest/.MainActivity: +656ms
I/Timeline( 7421): Timeline: Activity_idle id: android.os.BinderProxy@14baf47f time:95470
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
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/JsMessageQueue( 7421): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/chromium( 7421): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7421): 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/CustomFrequencyManagerService(  887): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 887  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  887): mDVFSHelper.release()
I/Timeline(  887): Timeline: Activity_windows_visible id: ActivityRecord{29b5f68b u0 com.test.thalitest/.MainActivity t11} time:95674
D/CustomFrequencyManagerService(  887): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 887  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/jxcore_app_log( 7421): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259379584
D/JX-Cordova( 7421): jxcore cordova android initializing
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (7/8)
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (-2/8)
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
E/Adreno-ES20( 7421): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7421): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  887): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 887  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/BooksSync( 7348): Soft error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4984500897447644374&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7348): Sync error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4984500897447644374&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7348): Finished books sync
D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  887): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 66518, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  887): Killing 6701:com.sec.pcw.device/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  887): failed to open /acct/uid_1000/pid_6701/cgroup.procs: No such file or directory
E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/SecContentProvider2(  887): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  887): mCursor = null
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,I/GAV2    ( 7348): Thread[GAThread,5,main]: No campaign data found.
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,W/jxcore-log( 7421): Initializing JXcore engine
,W/jxcore-log( 7421): JXcore engine is ready
,W/jxcore-log( 7421): Starting JXcore engine
,E/auditd  ( 2091): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  887): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  887): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7485): MountEmulatedStorage()
E/Zygote  ( 7485): v2
I/libpersona( 7485): KNOX_SDCARD checking this for 1000
I/libpersona( 7485): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7485 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7485): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7485): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7485): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/TimaKeyStoreProvider( 7485): TimaSignature is unavailable
,D/ActivityThread( 7485): Added TimaKeyStore provider
,W/jxcore-log( 7421): Platform android
W/jxcore-log( 7421): 
,W/jxcore-log( 7421): Process ARCH arm
W/jxcore-log( 7421): 
,D/ResourcesManager( 7485): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7485):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7485):  SeDenialReceiver : File path = null
,I/ActivityManager(  887): Killing 6463:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,W/libprocessgroup(  887): failed to open /acct/uid_10034/pid_6463/cgroup.procs: No such file or directory
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7421): JXcore Cordova bridge is ready!
I/jxcore-log( 7421): 
,W/jxcore-log( 7421): JXcore engine is started
,I/Choreographer( 7421): Skipped 132 frames!  The application may be doing too much work on its main thread.
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  887): CMD_RSSI_POLL : out!
,I/jxcore-log( 7421): Toggling radios to true
I/jxcore-log( 7421): 
,D/BluetoothAdapter( 7421): enable()
,D/BluetoothAdapter( 7421): enable(): BT is already enabled..!
,D/WifiService(  887): New client listening to asynchronous messages
,I/WifiManager( 7421): packageName : com.test.thalitest
,D/SecContentProvider(  887): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  887): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  887): mCursor = null
,D/WifiService(  887): setWifiEnabled: true pid=7421, uid=10367
E/WifiService(  887): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  887): Permission Denial: getCurrentUser() from pid=7421, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  887): Failed getting userId using ActivityManagerNative
W/WifiService(  887): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7421, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  887): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  887): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  887): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  887): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  887): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  887): name = wifi_on
,I/WifiService(  887): disconnect: pid=7421, uid=10367
I/wpa_supplicant( 1274): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7421): Radios toggled
I/jxcore-log( 7421): 
,I/wpa_supplicant( 1274): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1274): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1274): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  887): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1274): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1274): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1274): Disconnected - do not scan
I/wpa_supplicant( 1274): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  887): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  887): InactiveState{ what=143375 }
D/WifiP2pService(  887): P2pEnabledState{ what=143375 }
V/AlarmManager(  887): waitForAlarm result :4
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/CommandListener(  278): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1673): Read error: ssl=0xad342600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1673): SSL shutdown failed: ssl=0xad342600: I/O error during system call, Broken pipe
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  887): updateNetworkInfo()
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/WifiTrafficPoller(  887): evaluateTrafficStatsPolling
I/CLocInfoService(  887): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
E/ConnectivityService(  887): updateNetworkInfo()
D/ConnectivityService(  887): ignoring duplicate network state non-change
,D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/WifiStateMachine(  887): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1274): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1274): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1274): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1274): First Scan Start
,I/wpa_supplicant( 1274): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  887): ConnectModeState: Network connection lost 
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,D/ConnectivityService(  887): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  887): InactiveState{ what=143375 }
D/WifiP2pService(  887): P2pEnabledState{ what=143375 }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-9ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Forcing reevaluation
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Validated
,I/Hs20UtilService( 1306): Starting #6
,I/Hs20UtilService( 1306): Message received 5007
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  887): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  887): calling update connectivity
,D/ConnectivityService(  887):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  887):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/CommandListener(  278): Clearing all IP addresses on wlan0
D/ConnectivityService(  887): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/EntConnectivity(  887): Not allowed due to - mEnabled false
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Disconnected - quitting
,E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524292
,D/WifiStateMachine(  887): updateConfiguredNetworkExpiration - currTime: 1449681153430
D/WifiStateMachine(  887): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,I/WifiTrafficPoller(  887): evaluateTrafficStatsPolling
E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/CLocInfoService(  887): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  887): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  887): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiNetworkAgent(  887): NetworkAgent: NetworkAgent channel lost
,D/TelephonyNetworkFactory( 1465): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info"NG700"
,D/CSLegacyTypeTracker(  887): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  887): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/SecContentProvider2(  887): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  887): mCursor = null
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  887): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2(  887): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  887): mCursor = null
D/SmartBondingService(  887): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  887): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  887): getSBEnabled() enabled =false
D/SmartBondingService(  887): getSBEnabled() enabled =false
D/SmartBondingService(  887): getSBEnabled() enabled =false
,I/Hs20UtilService( 1306): Starting #7
,I/Hs20UtilService( 1306): Message received 5007
,V/NetworkStats(  887): updateIfacesLocked()
V/NetworkStats(  887): performPollLocked(flags=0x1)
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
E/ConnectivityService(  887): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/NetworkStatsFactory(  887): UpdateStatsForKnox
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  887): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  887): currentTimeMillis() cache hit
,D/NtpTrustedTime(  887): currentTimeMillis() cache hit
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
,V/NetworkStats(  887): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
,V/NetworkStats(  887): performPollLocked() took 8ms
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6592): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6592): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6592): [1] 5.onFinished: Scheduling replication attempt 2.
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2102): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ApplicationPolicy(  887): updateDataUsageMap
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,D/Tethering(  887): MasterInitialState.processMessage what=3
,I/SystemBroadcastReceiver( 7081): [#DCM#] [DCM_Performance] onReceive completed in time  4890 microsec. 
,I/SystemBroadcastReceiver( 7081): [#DCM#] Calling notifyListeners. 
,D/SmartBondingService(  887): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  887): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  887): getSBEnabled() enabled =false
D/SmartBondingService(  887): getSBEnabled() enabled =false
,D/SmartBondingService(  887): getSBEnabled() enabled =false
I/CLocInfoService(  887): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  887): CLoinfo wifi false
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5343): type=WIFI subType= reason=null isConnected=false
,I/DCMController( 7081): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,I/DCMController( 7081): [#DCM#] setIsConnectedForExtractors 
,W/SLocation(  887): No Active Data Connection
,E/Zygote  ( 7535): MountEmulatedStorage()
I/libpersona( 7535): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7535): v2
I/libpersona( 7535): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7535 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7535): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7535): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7535): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  887): getNetworkEnabled : wifi : true mobile : true
,D/TimaKeyStoreProvider( 7535): TimaSignature is unavailable
,D/ActivityThread( 7535): Added TimaKeyStore provider
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7535): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/DBG_DM  ( 3856): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3856): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/PCWCLIENTTRACE_LOG( 7535): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 7535): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7535): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 7535): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7535): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7535): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7535): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7535): noConnectivity : true
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7556): MountEmulatedStorage()
E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
E/Zygote  ( 7556): v2
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
I/libpersona( 7556): KNOX_SDCARD checking this for 10002
I/libpersona( 7556): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7556 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 4810:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,I/SELinux ( 7556): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7556): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7556): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7556): TimaSignature is unavailable
,D/ActivityThread( 7556): Added TimaKeyStore provider
,D/ResourcesManager( 7556): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_4810/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 6722:com.policydm/1000 (adj 15): bgCount ##41
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7573): MountEmulatedStorage()
,E/Zygote  ( 7573): v2
I/libpersona( 7573): KNOX_SDCARD checking this for 1000
I/libpersona( 7573): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7573 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7573): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7573): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7573): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/TimaKeyStoreProvider( 7573): TimaSignature is unavailable
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
D/ActivityThread( 7573): Added TimaKeyStore provider
D/ResourcesManager( 7573): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
W/libprocessgroup(  887): failed to open /acct/uid_1000/pid_6722/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7573): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7573): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7573): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7573): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7573): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7573): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/wpa_supplicant( 1274): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 1274): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1274): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1274): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  887): [1,449,681,154,462 ms] noteScanEnd no scan source
,E/WifiStateMachine(  887): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3a253bac sup_state=SCANNING debouncing=false
,I/CLocInfoService(  887): External Intent Received android.net.wifi.SCAN_RESULTS
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/WifiStateMachine(  887): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/WifiStateMachine(  887): setDetailed state send new extra info0x
,D/SecContentProvider2(  887): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  887): mCursor = null
,E/Zygote  ( 7592): MountEmulatedStorage()
,E/Zygote  ( 7592): v2
I/libpersona( 7592): KNOX_SDCARD checking this for 10011
I/libpersona( 7592): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7592 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7592): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7592): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7592): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7592): TimaSignature is unavailable
,D/ActivityThread( 7592): Added TimaKeyStore provider
,I/wpa_supplicant( 1274): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1274): Associated with C0.AA.48
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  887): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  887): mCursor = null
,D/ResourcesManager( 7592): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 1274): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  887): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  887): mCursor = null
,I/wpa_supplicant( 1274): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1274): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1274): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1274): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1274): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1274): Blacklist: Clear (temp) 
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  887): Network connection established
,D/WifiNative-HAL(  887): callSECApiVoid - ID [50]
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  887): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  887): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  887): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  887): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  887): Got NetworkAgent Messenger
D/ConnectivityService(  887): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  887): updateNetworkInfo()
,D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  887): NetworkAgent connected
E/WifiStateMachine(  887): L2ConnectedState "NG700" nid=0
,E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/PowerManagerService(  887): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1172 (0x0)
,I/ActivityManager(  887): Killing 5245:com.sec.spp.push/u0a38 (adj 15): bgCount ##41
,I/FOTA_Client( 7592): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,E/WifiStateMachine(  887): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  887): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/FOTA_Client( 7592): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/CommandListener(  278): Setting iface cfg
,E/WifiStateMachine(  887): Start Dhcp Watchdog 2
,D/SecContentProvider2(  887): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  887): mCursor = null
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  887): calculateWifiScore() report new score 60
,I/WifiStateMachine(  887): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  887): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  887): CMD_RSSI_POLL : out!
,D/ConnectivityService(  887): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  887): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/FOTA_Client( 7592): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7592): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7592): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7612): MountEmulatedStorage()
E/Zygote  ( 7612): v2
I/libpersona( 7612): KNOX_SDCARD checking this for 10019
I/libpersona( 7612): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7612 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6011:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/SELinux ( 7612): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7612): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/libprocessgroup(  887): failed to open /acct/uid_10038/pid_5245/cgroup.procs: No such file or directory
,E/SELinux ( 7612): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  887): do suspend false
,D/SecContentProvider2(  887): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  887): mCursor = null
,D/TimaKeyStoreProvider( 7612): TimaSignature is unavailable
D/WifiP2pService(  887): InactiveState{ what=143375 }
D/WifiP2pService(  887): P2pEnabledState{ what=143375 }
,D/ActivityThread( 7612): Added TimaKeyStore provider
,D/ResourcesManager( 7612): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7612): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7612): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449681154734
,I/KLMS-2.4.503: ( 7612): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7612): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7612): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  887): Killing 6742:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  887): failed to open /acct/uid_10042/pid_6011/cgroup.procs: No such file or directory
,E/Zygote  ( 7627): MountEmulatedStorage()
E/Zygote  ( 7627): v2
I/libpersona( 7627): KNOX_SDCARD checking this for 10037
,I/libpersona( 7627): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7627 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/SELinux ( 7627): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7627): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7627): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7627): TimaSignature is unavailable
,D/ActivityThread( 7627): Added TimaKeyStore provider
,D/ResourcesManager( 7627): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7627): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  887): failed to open /acct/uid_10045/pid_6742/cgroup.procs: No such file or directory
,E/Zygote  ( 7642): MountEmulatedStorage()
E/Zygote  ( 7642): v2
I/libpersona( 7642): KNOX_SDCARD checking this for 1000
I/libpersona( 7642): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7642 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6763:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 7642): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7642): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7642): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/dhcpcd  ( 7650): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7650): version 5.5.6 starting
,E/dhcpcd  ( 7650): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/TimaKeyStoreProvider( 7642): TimaSignature is unavailable
,D/ActivityThread( 7642): Added TimaKeyStore provider
,D/ResourcesManager( 7642): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,W/libprocessgroup(  887): failed to open /acct/uid_10051/pid_6763/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7650): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7650): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7650): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7650): bssid match
,I/dhcpcd  ( 7650): wlan0: rebinding lease of 192.168.1.135
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7672): MountEmulatedStorage()
E/Zygote  ( 7672): v2
I/libpersona( 7672): KNOX_SDCARD checking this for 10038
I/libpersona( 7672): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7672 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6780:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/art     (  317): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 270us total 15.007ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 262us total 8.490ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 7.583ms
,I/SELinux ( 7672): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7672): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7672): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 7650): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dhcpcd  ( 7650): wlan0: leased 192.168.1.135 for 86400 seconds
,D/TimaKeyStoreProvider( 7672): TimaSignature is unavailable
W/libprocessgroup(  887): failed to open /acct/uid_10058/pid_6780/cgroup.procs: No such file or directory
D/ActivityThread( 7672): Added TimaKeyStore provider
E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  887): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/ResourcesManager( 7672): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/SPPClientService( 7672): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7672): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7672): PushLog.txt file is not deleted.
,D/SPPClientService( 7672): PushLog.txt file is not deleted.
D/SPPClientService( 7672): ============PushLog. stop!
,E/SPPClientService( 7672): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7712): MountEmulatedStorage()
I/ActivityManager(  887): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7712 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7712): v2
I/libpersona( 7712): KNOX_SDCARD checking this for 10045
I/libpersona( 7712): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Killing 6190:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SELinux ( 7712): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7712): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7712): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 7672): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 7712): TimaSignature is unavailable
,D/ActivityThread( 7712): Added TimaKeyStore provider
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  887): InactiveState{ what=143375 }
,D/WifiP2pService(  887): P2pEnabledState{ what=143375 }
E/WifiStateMachine(  887): WifiStateMachine DHCP successful
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/ConnectivityService(  887): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  887): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiStateMachine(  887): Not connected state, yet.
E/WifiStateMachine(  887): VerifyingLinkState enter
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  887): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine(  887): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  887): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  887): callSECApiInt - ID [210]
,D/ResourcesManager( 7712): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  887): updateNetworkInfo()
,D/ConnectivityService(  887): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  887): Adding iface wlan0 to network 503
,I/CLocInfoService(  887): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  887): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  887): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  887): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  887): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  887): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,W/libprocessgroup(  887): failed to open /acct/uid_1000/pid_6190/cgroup.procs: No such file or directory
,E/WifiStateMachine(  887): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine(  887): Now, connected state.
E/WifiStateMachine(  887): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
E/WifiStateMachine(  887): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  887): evaluateTrafficStatsPolling
,I/CLocInfoService(  887): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiTrafficPoller(  887): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  887): mBoosterFLAG : 0
I/WifiTrafficPoller(  887): current booster mode : FullMode
,E/WifiStateMachine(  887): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiNative-HAL(  887): callSECApiVoid - ID [212]
,I/CLocInfoService(  887): External Intent Received android.net.wifi.STATE_CHANGE
D/ConnectivityService(  887): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/ConnectivityService(  887): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
E/WifiStateMachine(  887): ConnectedState Enter  mScreenOn=true scanperiod=20000
,D/ConnectivityService(  887): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
I/WifiStateMachine(  887): REQUEST_POWER_SAVE_ON
,E/ConnectivityService(  887): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  887): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  887): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  278): QcRouteController
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,V/        (  278): QcRouteController
,V/        (  278): QcRouteController
,I/SA      ( 7712): [SSP] onCreated
,I/SA      ( 7712): [TPM] There is no property file
,V/        (  278): QcRouteController
,I/SA      ( 7712): [SCU] isHaveSA() - false
,I/SA      ( 7712): [TPM] getModelProperty : null
,I/SA      ( 7712): [TPM] getCSCProperty : null
,I/SA      ( 7712): [DM] init START
,I/SA      ( 7712): [DM] This device is not a Vodafone
,W/ResourceType( 7712): Failure getting entry for 0x7f06000f (t=5 e=15) (error -75)
,W/ResourceType( 7712): Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
W/ResourceType( 7712): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 7712): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 7712): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 7712): Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
W/ResourceType( 7712): Failure getting entry for 0x7f060013 (t=5 e=19) (error -75)
,V/        (  278): QcRouteController
,W/ResourceType( 7712): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7712): Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
W/ResourceType( 7712): Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
W/ResourceType( 7712): Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
,W/ResourceType( 7712): Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
W/ResourceType( 7712): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 7712): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7712): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 7712): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 7712): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 7712): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 7712): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 7712): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,V/        (  278): QcRouteController
,I/SA      ( 7712): [SCU] isHaveSA() - false
,I/SA      ( 7712): support phone number id : false
V/        (  278): QcRouteController
,I/SA      ( 7712): [DM] init END
I/SA      ( 7712): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7712): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 7712): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7712): [SLFUCHKMGR] constructor called
,I/SA      ( 7712): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7712): [OR] == isSIMCardReady false ==
I/SA      ( 7712): [SCU] == networkStateCheck == false
I/SA      ( 7712): [OR] onReceive END
,V/        (  278): QcRouteController
,I/ActivityManager(  887): Killing 6527:com.sec.chaton/u0a86 (adj 15): bgCount ##41
,D/ConnectivityService(  887): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  887): calling update connectivity
,D/ConnectivityService(  887): ignoring duplicate network state non-change
E/ConnectivityService(  887): updateNetworkInfo()
D/ConnectivityService(  887): ignoring duplicate network state non-change
E/ConnectivityService(  887): updateNetworkInfo()
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  887): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  887): calling update connectivity
D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Validated
D/ConnectivityService(  887):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  887):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  887):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  887): currentScore = 0, newScore = 60
,D/ConnectivityService(  887):    accepting network in place of null
D/ConnectivityService(  887): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1465): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/SSRM:m  (  887): SIOP:: AP = 400, PST = 426, CUR = 300
,E/CSLegacyTypeTracker(  887): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  887): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/ActivityManager(  887): Failed to clear dns cache for: com.sec.chaton
,D/accuweather( 7260): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7260): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/ConnectivityService(  887): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/accuweather( 7260): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/SmartBondingService(  887): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  887): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  887): getSBEnabled() enabled =false
D/SmartBondingService(  887): getSBEnabled() enabled =false
D/SmartBondingService(  887): getSBEnabled() enabled =false
V/NetworkStats(  887): updateIfacesLocked()
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
V/NetworkStats(  887): performPollLocked(flags=0x1)
,D/ConnectivityService(  887): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  887): getNetworkEnabled : wifi : true mobile : true
D/NetworkStatsFactory(  887): UpdateStatsForKnox
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 7260): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7260): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7260): [KK AccuPhone]>>> RM:136 [0:0]  V init 
D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  887): calling update connectivity
D/ConnectivityService(  887):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  887):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  887): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  887): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  887):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  887):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  887): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
D/ConnectivityService(  887): calling update connectivity
V/NetworkStats(  887): performPollLocked() took 3ms
D/ConnectivityService(  887):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  887):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  887): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/NtpTrustedTime(  887): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
V/NetworkStats(  887): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
,D/daemonapp( 1330): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,W/libprocessgroup(  887): failed to open /acct/uid_10086/pid_6527/cgroup.procs: No such file or directory
,D/accuweather( 7260): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1330): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7260): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1330): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7260): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7260): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/Zygote  ( 7752): MountEmulatedStorage()
,E/Zygote  ( 7752): v2
I/libpersona( 7752): KNOX_SDCARD checking this for 1000
I/libpersona( 7752): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7752 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7752): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7752): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7752): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7752): TimaSignature is unavailable
,D/ActivityThread( 7752): Added TimaKeyStore provider
,D/ResourcesManager( 7752): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7752): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7752): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7752): premStatus:2
,I/KnoxUsageLogPro( 7752): isEulaShown : false
I/KnoxUsageLogPro( 7752): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7767): MountEmulatedStorage()
E/Zygote  ( 7767): v2
I/libpersona( 7767): KNOX_SDCARD checking this for 10086
I/libpersona( 7767): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.NetStateReceiver: pid=7767 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6805:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,I/SELinux ( 7767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7767): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7767): TimaSignature is unavailable
,D/ActivityThread( 7767): Added TimaKeyStore provider
,W/libprocessgroup(  887): failed to open /acct/uid_10098/pid_6805/cgroup.procs: No such file or directory
,D/ResourcesManager( 7767): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7767): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/PushModule( 7767): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 7767): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 7767): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 7767): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 7767): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  887): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 7767): [1][a] ChatONV isn't installed.
D/ChatON  ( 7767): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7789): MountEmulatedStorage()
,E/Zygote  ( 7789): v2
I/libpersona( 7789): KNOX_SDCARD checking this for 10088
I/libpersona( 7789): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7789 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6858:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,E/SMD     (  285): DCD ON
,I/SELinux ( 7789): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7789): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7789): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7789): TimaSignature is unavailable
,D/ActivityThread( 7789): Added TimaKeyStore provider
,W/libprocessgroup(  887): failed to open /acct/uid_10033/pid_6858/cgroup.procs: No such file or directory
,D/ResourcesManager( 7789): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/SmartBondingService(  887): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  887): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  887): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  887): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  887): CLocinfo wifi true 
D/SmartBondingService(  887): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  887): getSBEnabled() enabled =false
D/SmartBondingService(  887): getSBEnabled() enabled =false
D/SmartBondingService(  887): getSBEnabled() enabled =false
D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2102): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  887): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2170): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2170): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3856): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3856): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  887): Killing 6834:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,D/Headlines( 5492): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5492): getCountryCode(): countryCode = DE
,I/SystemBroadcastReceiver( 7081): [#DCM#] [DCM_Performance] onReceive completed in time  1131 microsec. 
,I/SystemBroadcastReceiver( 7081): [#DCM#] Calling notifyListeners. 
I/DCMController( 7081): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7081): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DatabaseRebuilderTask( 7081): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Headlines( 5492): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5492): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5492): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5492): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5492): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5492): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5492): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7806): MountEmulatedStorage()
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7806 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7806): v2
I/libpersona( 7806): KNOX_SDCARD checking this for 10128
D/SecContentProvider2(  887): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  887): mCursor = null
I/libpersona( 7806): KNOX_SDCARD not a persona
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5343): type=WIFI subType= reason=null isConnected=true
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/FrameworkService( 7081): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7081): [#DCM#] onCreate FrameworkService end 
I/DCMConfig( 7081): [#DCM#] getSuccessState = true
I/FrameworkService( 7081): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
I/IntentHandler( 7081): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,I/SELinux ( 7806): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7806): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7806): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/SystemUtils( 7081): [#DCM#] LM: false,AM:723394560
,I/DCMThreadPoolExecutor( 7081): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7081): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@7b4107c is submitted
,I/FrameworkService( 7081): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 35977 mirosec. 
,D/TimaKeyStoreProvider( 7806): TimaSignature is unavailable
,D/ActivityThread( 7806): Added TimaKeyStore provider
,W/libprocessgroup(  887): failed to open /acct/uid_10099/pid_6834/cgroup.procs: No such file or directory
,I/art     (  887): Explicit concurrent mark sweep GC freed 66420(3MB) AllocSpace objects, 8(258KB) LOS objects, 30% free, 36MB/52MB, paused 1.418ms total 84.888ms
I/art     (  887): WaitForGcToComplete blocked for 84.895ms for cause Explicit
,D/ResourcesManager( 7806): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/art     (  887): Explicit concurrent mark sweep GC freed 5316(347KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 1.424ms total 72.739ms
,I/DatabaseRebuilderTask( 7081): [#DCM#] createLuceneReader done 
I/DatabaseRebuilderTask( 7081): [#DCM#] resyncLocation   
I/DatabaseRebuilderTask( 7081): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
,I/DatabaseRebuilderTask( 7081): [#DCM#] topDocs hits = 0
I/DatabaseRebuilderTask( 7081): [#DCM#] No of Location data to be added:  0
,I/DatabaseRebuilderTask( 7081): [#DCM#] releaseLuceneReader done 
I/DatabaseRebuilderTask( 7081): [#DCM#] Starting media manager do operation 
I/SystemUtils( 7081): [#DCM#] setHeavySharedPref set as  false
,I/IntentHandler( 7081): [#DCM#] Stopping service with ids up to  1
,I/DCMThreadPoolExecutor( 7081): [#DCM#] afterExecute FutureTask
,I/DCMController( 7081): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@7b4107c
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7806): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7806): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7806): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7806): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/WebViewFactory( 7806): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7806): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7806): Loading: webviewchromium
,I/LibraryLoader( 7806): Time to load native libraries: 4 ms (timestamps 1256-1260)
,I/LibraryLoader( 7806): Expected native library version number "",actual native library version number ""
,D/ConnectivityService(  887): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,V/WebViewChromiumFactoryProvider( 7806): Binding Chromium to main looper Looper (main, tid 1) {98f8ac8}
,I/LibraryLoader( 7806): Expected native library version number "",actual native library version number ""
,I/chromium( 7806): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7806): Initializing chromium process, renderers=0
,W/art     ( 7806): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid( 7806): Requires BLUETOOTH permission
,W/chromium( 7806): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7806): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7806): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/Adreno-EGL( 7806): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7806): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7806): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7806): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7806): Remote Branch: 
I/Adreno-EGL( 7806): Local Patches: 
I/Adreno-EGL( 7806): Reconstruct Branch: 
,I/NSApplication( 7806): Starting up...
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7868): MountEmulatedStorage()
E/Zygote  ( 7868): v2
I/libpersona( 7868): KNOX_SDCARD checking this for 10138
I/libpersona( 7868): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7868 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6901:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,I/SELinux ( 7868): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7868): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7868): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7868): TimaSignature is unavailable
,D/ActivityThread( 7868): Added TimaKeyStore provider
,W/libprocessgroup(  887): failed to open /acct/uid_10003/pid_6901/cgroup.procs: No such file or directory
,D/ResourcesManager( 7868): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7868): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7868): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7868): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7868): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7868): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7868): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7886): MountEmulatedStorage()
,E/Zygote  ( 7886): v2
I/libpersona( 7886): KNOX_SDCARD checking this for 10163
I/libpersona( 7886): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7886 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6915:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,I/SELinux ( 7886): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7886): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7886): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7886): TimaSignature is unavailable
,D/ActivityThread( 7886): Added TimaKeyStore provider
,D/ResourcesManager( 7886): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,W/ResourcesManager( 7886): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7886): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7886): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7886): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  887): failed to open /acct/uid_10020/pid_6915/cgroup.procs: No such file or directory
,D/RCPManagerService(  887): exchangeData() failure , invalid userId
,D/RCPManagerService(  887): exchangeData() failure , invalid userId
,D/RCPManagerService(  887): exchangeData() failure , invalid userId
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7908 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,E/Zygote  ( 7908): MountEmulatedStorage()
,E/Zygote  ( 7908): v2
I/libpersona( 7908): KNOX_SDCARD checking this for 10078
I/libpersona( 7908): KNOX_SDCARD not a persona
,I/SELinux ( 7908): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7908): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7908): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  887): exchangeData() failure , invalid userId
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/TimaKeyStoreProvider( 7908): TimaSignature is unavailable
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ActivityThread( 7908): Added TimaKeyStore provider
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/RCPManagerService(  887): exchangeData() failure , invalid userId
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
D/RCPManagerService(  887): exchangeData() failure , invalid userId
,I/ActivityManager(  887): Killing 6928:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,D/ResourcesManager( 7908): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/BadgeProvider( 7908): onCreate
D/BadgeProvider( 7908): DatabaseHelper
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,D/SecurityLogAgent( 7485): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7485): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7485): StateMachine : Current State = 1
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7485): StateMachine : Changed Current State = 1
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
I/ActivityManager(  887): Killing 6949:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,D/BadgeProvider( 7908): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,D/BadgeProvider( 7908): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7908): sendNotify, [notify] : null
D/BadgeProvider( 7908): update, [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1471): reloadBadges entered.
,D/BadgeProvider( 7908): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7908): update, [UpdateCount] : 1
D/com.peel.receiver.ConnectivityActionReceiver( 1754): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): last run: 1449670518662 -- System.currentTimeMillis()-last_run: 10638369
D/com.peel.receiver.ConnectivityActionReceiver( 1754): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): ... skip last_72_check
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,E/Zygote  ( 7930): MountEmulatedStorage()
E/Zygote  ( 7930): v2
I/libpersona( 7930): KNOX_SDCARD checking this for 10178
I/libpersona( 7930): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7930 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7886): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,I/SELinux ( 7930): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  887): failed to open /acct/uid_1000/pid_6928/cgroup.procs: No such file or directory
,I/SELinux ( 7930): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7930): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/TimaKeyStoreProvider( 7930): TimaSignature is unavailable
,D/ActivityThread( 7930): Added TimaKeyStore provider
,D/ResourcesManager( 7930): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,W/ActivityManager(  887): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/libprocessgroup(  887): failed to open /acct/uid_10112/pid_6949/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 6967:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2442): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  887): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  887): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  887): identical MTU - not setting
D/ConnectivityService(  887): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  887): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
V/        (  278): QcRouteController
E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService(  887): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  887): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  887): getSBEnabled() enabled =false
D/SmartBondingService(  887): getSBEnabled() enabled =false
D/SmartBondingService(  887): getSBEnabled() enabled =false
D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2442): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/        (  278): QcRouteController
,W/libprocessgroup(  887): failed to open /acct/uid_10118/pid_6967/cgroup.procs: No such file or directory
,W/NetworkManagementService(  887): route cmd failed: 
W/NetworkManagementService(  887): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  887): '
W/NetworkManagementService(  887): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  887): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  887): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  887): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  887): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  887): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  887): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  887): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  887): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  887): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  887): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  887): calling update connectivity
D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  887):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  887):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  887): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WaitQueueForNetworkActivate( 7057): notifyNetworkActivated
D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  887): calling update connectivity
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524295
D/ConnectivityService(  887):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  887):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  887): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524295
D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 7057): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  887): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
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
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/hcjo    ( 7057): AutoUpdateManager:IDLE:execute
,I/Hs20UtilService( 1306): Starting #8
,D/InitializeManagerStateMachine( 7057): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7057): exit::IDLE
D/InitializeManagerStateMachine( 7057): entry::NETWORK_CHECK
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 1306): Message received 5007
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/InitializeManagerStateMachine( 7057): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7057): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7057): entry::CHECK_COUNTRY_INFO
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7057): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7057): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7057): entry::SUCCESS
D/hcjo    ( 7057): AutoUpdateManager:INITCHECK:onInitializeSuccess
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,D/hcjo    ( 7057): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7057): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/Hs20UtilService( 1306): Starting #9
I/Hs20UtilService( 1306): Message received 5007
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,D/InitializeManagerStateMachine( 7057): exit::SUCCESS
D/InitializeManagerStateMachine( 7057): entry::IDLE
,I/Hs20UtilService( 1306): Starting #10
,I/Hs20UtilService( 1306): Message received 5007
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1306): Starting #11
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 1306): Message received 5007
,I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  887): callSECApi what=220
D/WifiStateMachine(  887): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 7535): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7535): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7535): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7535): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/DIAGMON_AGENT( 7573): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7573): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService(  887): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=887
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/FOTA_Client( 7592): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7592): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7592): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7592): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7592): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/KLMS-2.4.503: ( 7612): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7612): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449681157538
,I/KLMS-2.4.503: ( 7612): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7612): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7612): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7612): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/KLMS-2.4.503: ( 7612): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7627): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,E/SPPClientService( 7672): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7712): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  887): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SA      ( 7712): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7712): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SA      ( 7712): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7712): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7712): [SCU] == networkStateCheck == true
,I/SA      ( 7712): [DM] getCountryCodeFromCSC : DE
I/SA      ( 7712): isChinaCountryCode : false
I/SA      ( 7712): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7712): [OR] == networkStateCheck true ==
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SA      ( 7712): [OR] GetMyCountryZoneTask
,I/SA      ( 7712): [OR] onReceive END
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/accuweather( 7260): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7260): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/SA      ( 7712): [SRS] prepareGetMyCountryZone
,I/KnoxUsageLogPro( 7752): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7752): premStatus:2
,I/KnoxUsageLogPro( 7752): isEulaShown : false
I/KnoxUsageLogPro( 7752): KnoxUsageReceiver onReceive : not Processible, just return
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SA      ( 7712): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7712): [SSP] query invoked
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/Headlines( 5492): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5492): getCountryCode(): countryCode = DE
,D/Headlines( 5492): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5492): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/HeadlinesCardManager( 5492): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5492): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5492): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5492): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5492): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SA      ( 7712): [TPMU] GetMccFromDB : null
,I/SA      ( 7712): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7712): [TPM] isNoProxy(default) : true
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7868): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7868): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7868): PeriphStartReceiver.onReceive - no need to start
,E/File    ( 7712): fail readDirectory() errno=2
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  887): exchangeData() failure , invalid userId
D/RCPManagerService(  887): exchangeData() failure , invalid userId
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7485): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7485): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7485): StateMachine : Current State = 1
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/SecurityLogAgent( 7485): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 1754): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): last run: 1449670518662 -- System.currentTimeMillis()-last_run: 10639095
D/com.peel.receiver.ConnectivityActionReceiver( 1754): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): ... skip last_72_check
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ChimeraCfgMgr( 2442): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2442): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7057): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7057): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7057): exit::IDLE
D/InitializeManagerStateMachine( 7057): entry::NETWORK_CHECK
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/InitializeManagerStateMachine( 7057): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/LockPatternUtilsCache( 1172): value : false
D/InitializeManagerStateMachine( 7057): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 7057): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7057): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7057): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7057): entry::SUCCESS
D/hcjo    ( 7057): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7057): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7057): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7057): exit::SUCCESS
D/InitializeManagerStateMachine( 7057): entry::IDLE
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
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
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
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
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/SA      ( 7712): [RC New] Execute method=[GET] start
,I/SA      ( 7712): [RC New] Security=[true]
,I/System.out( 7712): Thread-1280(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7712): Thread-1280(ApacheHTTPLog):isShipBuild true
,I/System.out( 7712): Thread-1280(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,W/ProcessCpuTracker(  887): Skipping unknown process pid 7977
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  887): [s] UserActivityState : 1 -> 2
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  887): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  887): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,I/SA      ( 7712): [RC New] [v2liruge] api execute + 661
I/SA      ( 7712): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7712): AsyncTask #1 calls detatch()
,I/SA      ( 7712): [ODM] saveOpenData( GEO_IP, PL )
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/SA      ( 7712): [OCP] update openData : PL
,I/SA      ( 7712): [TPMU] getNetworkMcc : 
,I/SA      ( 7712): [SCU] saveMccToPreferece Start
,I/SA      ( 7712): [SCU] RegionMCC : 260
I/SA      ( 7712): [SSP] query invoked
,I/SA      ( 7712): [TPMU] GetMccFromDB : null
,I/SA      ( 7712): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7712): [SCU] saveMccToPreferece End
,I/SA      ( 7712): [RC New] executeRequest [v2liruge] end. 728
I/SA      ( 7712): [RC New] Execute end
I/SA      ( 7712): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7712): [OR] GetMyCountryZoneTask Success
,E/Watchdog(  887): !@Sync 3
,V/AlarmManager(  887): waitForAlarm result :4
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/dhcpcd  ( 7650): wlan0: sending IPv6 Router Solicitation
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/GCM     ( 1673): Connected
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1673): Message class com.google.f.a.a.p
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,V/AlarmManager(  887): waitForAlarm result :8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1673): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/Search.LoginHelper( 1571): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7421): Test app app.js loaded
I/jxcore-log( 7421): 
,I/Choreographer( 7421): Skipped 430 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7421): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7421): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  887): CMD_RSSI_POLL : out!
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PowerManagerService(  887): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 887) eventTime = 105722
,D/PowerManagerService(  887): [s] UserActivityState : 2 -> 1
,D/PowerManagerService(  887): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=887 (0x0)
D/PowerManagerService(  887): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=887, ws=WorkSource{10059}) (elapsedTime=3478)
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
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
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
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
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
D/LockPatternUtilsCache( 1172): value : false
,I/GAV4    ( 7806): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
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
,I/SurfaceFlinger(  249): id=16 Removed Toast (8/8)
,I/SurfaceFlinger(  249): id=16 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7535): mConnectivityHandler : connected
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7535): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 7535): ================================================
I/CSTORAGE( 7535):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 7535): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7535): [GetString-S]
E/art     ( 7535): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 7535): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7535): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7535): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7535): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7535): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7535): [ensureRegistration] - No Samsung account
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7650): wlan0: sending IPv6 Router Solicitation
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  887): CMD_RSSI_POLL : out!
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/SSRM:m  (  887): SIOP:: AP = 400, PST = 424, CUR = 300
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  887): CMD_RSSI_POLL : out!
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8,
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7650): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7650): wlan0: no IPv6 Routers available
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 7057): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7057): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7057): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,V/BitmapFactory( 1172): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_out.png
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/hcjo    ( 7057): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7057): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7057): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7057): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7057): entry::IDLE
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,D/PreloadUpdateManagerStateMachine( 7057): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 7057): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7057): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7057): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7057): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7057): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7057): entry::IDLE
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false),
,D/StatusBar.NetworkController( 1172): applyOpen,
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen,
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  887): CMD_RSSI_POLL : out!
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen,
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/FactoryTest( 6436): Not factory mode
,D/FactoryTest( 6436): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6436): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6436): still no open session command from host, so toast
,W/ContextImpl( 6436): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6436): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6436): Timeline: Activity_launch_request id:com.android.settings time:115475
,E/PersonaManagerService(  887): inState():  stateMachine is null !!
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  887): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  887): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 887  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  887): mDVFSHelper.acquire()
,I/SQLiteSecureOpenHelper( 3540): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3540): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/MTPRx   ( 6436): started activity for popup
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,D/ResourcesManager( 6436): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6436): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6436): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6436): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6436): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6436): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6436): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6436): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6436): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/ActivityManager(  887): Invalid thumbnail dimensions: 576x576
,D/InputMethodManagerService(  887): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  887): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@5a51b06 attribute=null, token = android.os.BinderProxy@27b4099
,I/SQLiteSecureOpenHelper( 3540): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3540): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6436): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6436): dev.kiessupport is : TRUE
,D/Activity( 6436): performCreate Call secproduct feature valuefalse
,D/Activity( 6436): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ActivityManager(  887): post active user change for 0
D/KnoxTimeoutHandler(  887): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  887): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/Timeline( 7421): Timeline: Activity_idle id: android.os.BinderProxy@14baf47f time:115734
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  887): CMD_RSSI_POLL : out!
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,V/AlarmManager(  887): waitForAlarm result :4
,D/CustomFrequencyManagerService(  887): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 887  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  887): mDVFSHelper.release()
D/CustomFrequencyManagerService(  887): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 887  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  887): Plugged
I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6592): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6592): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6592): [1] 5.onFinished: Scheduling replication attempt 3.
,D/CustomFrequencyManagerService(  887): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 887  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/SSRM:m  (  887): SIOP:: AP = 370, PST = 414, CUR = 300
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  887): CMD_RSSI_POLL : out!
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,V/AlarmManager(  887): waitForAlarm result :4
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  887): CMD_RSSI_POLL : out!
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  887): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  887): CMD_RSSI_POLL : out!
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  887): Plugged
I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  887): CMD_RSSI_POLL : out!
,D/PowerManagerService(  887): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  887): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  887): lcd : 6 +
,D/lights  (  887): lcd : 6 -
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,D/lights  (  887): lcd : 1 +
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/lights  (  887): lcd : 1 -
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,D/SSRM:m  (  887): SIOP:: AP = 340, PST = 400, CUR = 300
D/X       (  887): broadcastSiopLevelIntent:: currentSiopLevel = -1
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,D/ContentApp( 1224):  LEVEL : -1
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
I/SystemBroadcastReceiver( 7081): [#DCM#] [DCM_Performance] onReceive completed in time  25305 microsec. 
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,I/SystemBroadcastReceiver( 7081): [#DCM#] Calling notifyListeners. 
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/DCMPolicyManager( 7081): [#DCM#] onReceive action = EVENT_SIOP
,E/Zygote  ( 8065): MountEmulatedStorage()
,E/Zygote  ( 8065): v2
I/libpersona( 8065): KNOX_SDCARD checking this for 10054
I/libpersona( 8065): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8065 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 8065): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8065): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8065): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/TimaKeyStoreProvider( 8065): TimaSignature is unavailable
D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,D/ActivityThread( 8065): Added TimaKeyStore provider
,D/ResourcesManager( 8065): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8065): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8065): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8065): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8065): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8065): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SMD     (  285): DCD ON
,E/TranscodeReceiver( 8065): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8065): core_num = 4
,W/linker  ( 8065): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8065): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8065): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,D/videowall-Global( 8065): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8065):  SIOP_LEVEL: -1
,I/ActivityManager(  887): Killing 6983:com.samsung.helphub/1000 (adj 15): bgCount ##41
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,W/libprocessgroup(  887): failed to open /acct/uid_1000/pid_6983/cgroup.procs: No such file or directory
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  887): CMD_RSSI_POLL : out!
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/SMD     (  285): DCD ON
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/Watchdog(  887): !@Sync 4
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  887): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  887): CMD_RSSI_POLL : out!
,D/PowerManagerService(  887): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  887): Nap time (uid 1000)...
I/PowerManagerService(  887): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  887): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  887): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  887): SecHardwareInterface.setBatteryADC : false
D/InputManager-JNI(  887): setDeviceInteractive: 0
,D/PowerManagerService(  887): handleSandman : startDream()
,D/InputManager-JNI(  887): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  887): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,E/PowerManagerService(  887): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  887): Sleeping (uid 1000)...
D/PowerManagerService(  887): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  887): [input device light] setInputDeviceLightOn is called : 0
,D/InputManager-JNI(  887): sysfs_write -: /sys/class/input/event2/device/enabled: 0
D/PowerManagerService(  887): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  887): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  887): 	.unregisterCallback : 1, client=
,D/SContextService(  887): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@335244f4, Service = Auto Rotation, used = 1
,W/CAE     (  887): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  887): stop(ContextProvider.java:149)
,V/CAE     (  887): clear(AutoRotationRunner.java:182)
,V/CAE     (  887): disable(AutoRotationRunner.java:171)
,I/CAE     (  887): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  887): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  298): sendContextData: -78, 7, 0, 0
,D/CAE     (  887): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  887): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  887): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  887): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  887): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  887): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  887): removeSContextService() : service = Auto Rotation
D/SContextService(  887): ===== SContext Service List =====
D/SContextManager(  887):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@d02a9f4, service=Auto Rotation
,D/KeyguardViewMediator( 1172): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1172): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1172): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1172): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/KeyguardViewMediator( 1172): timeout : 5000
I/SQLiteSecureOpenHelper( 3540): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3540): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/DisplayPowerController(  887): ColorFade: onAnimationStart
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 0
D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
D/DisplayPowerController(  887): getFinalBrightness : 8 -> 0
,D/lights  (  887): lcd : 0 +
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 0
,D/lights  (  887): lcd : 0 -
,D/KeyguardViewMediator( 1172): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1172): handleNotifyScreenOff
,D/LightsService(  887): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 887) 
D/LightsService(  887): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  887): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  887): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  887): unregisterListener ::   
D/lights  (  887): led_pattern : 5 +
,D/BatteryService(  887): turn on LED for fully charged
,D/lights  (  887): led_pattern : 5 -
D/LightsService(  887): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  887): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  887): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
,I/CAE     (  887): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  887): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  298): sendContextData: -76, 13, -46, 0
,I/CAE     (  887): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 17, 13, 11,
,D/SensorHubManager(  887): SendSensorHubData: send data = -63, 14, 17, 13, 11
D/Sensorhubs(  298): sendContextData: -63, 14, 17, 13, 11
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  887):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  887): backgroundScan enabled=false startBackgroundScanIfNeeded:false
D/NotificationService(  887): ACTION_SCREEN_OFF
D/LightsService(  887): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 887) 
D/LightsService(  887): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,E/WifiStateMachine(  887): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  887): do suspend true
,D/LightsService(  887): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  887): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  887): unregisterListener ::   
D/LightsService(  887): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  292): adev_set_parameters: enter: screen_state=off
V/voice   (  292): voice_set_parameters: enter: screen_state=off
V/voice   (  292): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  292): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  292): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  292): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  292): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  887): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  887): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  887): Bridge Server is not available
,D/VolumePanel( 1172): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 1172): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1172): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1172): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,E/LightSensor(  887): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  887): mCallbacks.updateBrightness()
,D/DisplayPowerController(  887): getFinalBrightness : 8 -> 0
,D/PersonaManagerService(  887): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  887): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1459): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1172):      ACTION_SCREEN_OFF is finished!!!! 
,D/DisplayPowerState(  887): !@ ColorFade entry
,D/DisplayPowerController(  887): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  887): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
D/AutomaticBrightnessController(  887): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/AutomaticBrightnessController(  887): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  887): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
E/LightSensor(  887): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,E/StatusBar( 1172): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1172): dismissHelpPopup 
,D/SensorManager(  887): unregisterListener ::   
,E/Sensors (  887): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
D/accuweather( 2102): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2102): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2102): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/SensorManager(  887): unregisterListener ::   
,D/DisplayPowerController(  887): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  887): getFinalBrightness : 0 -> 0
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
I/DisplayManagerService(  887): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  887): Display changed displayId=0
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1172): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SystemBroadcastReceiver( 7081): [#DCM#] [DCM_Performance] onReceive completed in time  189 microsec. 
,I/SystemBroadcastReceiver( 7081): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7081): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 7081): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,W/ActivityManager(  887): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  887): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  887): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:m  (  887): SIOP:: AP = 330, PST = 385, CUR = 300
,I/rmt_storage(  274): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
I/rmt_storage(  274): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  274): wakelock acquired: 1, error no: 42
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
,I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 22
I/rmt_storage(  274): 
,I/rmt_storage(  274): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/PowerManagerService(  887): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SurfaceControl(  887): Excessive delay in setPowerMode(): 255ms
D/MISC PowerHAL(  887): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  887): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  887): Got set_interactive hint
,I/PowerManagerService(  887): [PWL] Off : 0s ago
I/PowerManagerService(  887): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  887): [PWL]     mDisplayReady : false
D/DisplayPowerController(  887): getFinalBrightness : 0 -> 0
D/PowerManagerService(  887): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  887): [PWL] sb release: PowerManagerService.Display
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  887): waitForAlarm result :4
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  887): stay LED for fully charged
D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     (  887): Explicit concurrent mark sweep GC freed 59031(3MB) AllocSpace objects, 18(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.803ms total 218.812ms
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1673): Explicit concurrent mark sweep GC freed 34242(2MB) AllocSpace objects, 22(1782KB) LOS objects, 39% free, 17MB/29MB, paused 870us total 64.468ms
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6592): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6592): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6592): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  887): waitForAlarm result :4
,D/KeyguardViewMediator( 1172): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1172): isKioskContainerExistOnDevice,
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/KeyguardViewMediator( 1172): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService(  887): [PWL] Off : 5s ago
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 330, PST = 374, CUR = 300,
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  887): [PWL] Off : 15s ago
,E/SMD     (  285): DCD ON
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :4
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1673): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6562): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6562): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6562): 	at kfv.a(PG:65)
E/HttpOperation( 6562): 	at kff.u(PG:385)
E/HttpOperation( 6562): 	at kfb.a(PG:29)
E/HttpOperation( 6562): 	at kff.l(PG:132)
E/HttpOperation( 6562): 	at dsf.a(PG:807)
E/HttpOperation( 6562): 	at fhk.a(PG:1126)
E/HttpOperation( 6562): 	at fhk.a(PG:908)
E/HttpOperation( 6562): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6562): 	at ihi.a(PG:22)
E/HttpOperation( 6562): 	at kft.a(PG:91)
E/HttpOperation( 6562): 	at kfv.a(PG:62)
E/HttpOperation( 6562): 	... 8 more
E/HttpOperation( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6562): 	at gde.c(Unknown Source)
E/HttpOperation( 6562): 	at gde.b(Unknown Source)
E/HttpOperation( 6562): 	at ihi.a(PG:19)
E/HttpOperation( 6562): 	... 10 more
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6562): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6562): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6562): 	at kfv.a(PG:65)
E/HttpOperation( 6562): 	at kff.u(PG:385)
E/HttpOperation( 6562): 	at kfb.a(PG:29)
E/HttpOperation( 6562): 	at kff.l(PG:132)
E/HttpOperation( 6562): 	at ieo.a(PG:43)
E/HttpOperation( 6562): 	at iep.a(PG:93)
E/HttpOperation( 6562): 	at fhn.a(PG:59)
E/HttpOperation( 6562): 	at lex.a(PG:85)
E/HttpOperation( 6562): 	at lex.b(PG:132)
E/HttpOperation( 6562): 	at fhk.a(PG:1146)
E/HttpOperation( 6562): 	at fhk.a(PG:908)
E/HttpOperation( 6562): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6562): 	at ihi.a(PG:22)
E/HttpOperation( 6562): 	at kft.a(PG:91)
E/HttpOperation( 6562): 	at kfv.a(PG:62)
E/HttpOperation( 6562): 	... 12 more
E/HttpOperation( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6562): 	at gde.c(Unknown Source)
E/HttpOperation( 6562): 	at gde.b(Unknown Source)
E/HttpOperation( 6562): 	at ihi.a(PG:19)
E/HttpOperation( 6562): 	... 14 more
,E/ExperimentLoader( 6562): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6562): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6562): 	at kfv.a(PG:65)
E/ExperimentLoader( 6562): 	at kff.u(PG:385)
E/ExperimentLoader( 6562): 	at kfb.a(PG:29)
E/ExperimentLoader( 6562): 	at kff.l(PG:132)
E/ExperimentLoader( 6562): 	at ieo.a(PG:43)
E/ExperimentLoader( 6562): 	at iep.a(PG:93)
E/ExperimentLoader( 6562): 	at fhn.a(PG:59)
E/ExperimentLoader( 6562): 	at lex.a(PG:85)
E/ExperimentLoader( 6562): 	at lex.b(PG:132)
E/ExperimentLoader( 6562): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6562): 	at fhk.a(PG:908)
E/ExperimentLoader( 6562): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6562): 	at ihi.a(PG:22)
E/ExperimentLoader( 6562): 	at kft.a(PG:91)
E/ExperimentLoader( 6562): 	at kfv.a(PG:62)
E/ExperimentLoader( 6562): 	... 12 more
E/ExperimentLoader( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6562): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6562): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6562): 	at ihi.a(PG:19)
E/ExperimentLoader( 6562): 	... 14 more
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/SSRM:m  (  887): SIOP:: AP = 320, PST = 365, CUR = 300
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6562): [getaccountstatus] Unexpected exception
E/HttpOperation( 6562): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6562): 	at kfv.a(PG:65)
E/HttpOperation( 6562): 	at kff.u(PG:385)
E/HttpOperation( 6562): 	at kfb.a(PG:29)
E/HttpOperation( 6562): 	at ixd.a(PG:248)
E/HttpOperation( 6562): 	at ixd.b(PG:206)
E/HttpOperation( 6562): 	at ixd.a(PG:175)
E/HttpOperation( 6562): 	at fig.a(PG:78)
E/HttpOperation( 6562): 	at lex.a(PG:85)
E/HttpOperation( 6562): 	at lex.b(PG:132)
E/HttpOperation( 6562): 	at fhk.a(PG:1146)
E/HttpOperation( 6562): 	at fhk.a(PG:908)
E/HttpOperation( 6562): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6562): 	at ihi.a(PG:22)
E/HttpOperation( 6562): 	at kft.a(PG:91)
E/HttpOperation( 6562): 	at kfv.a(PG:62)
E/HttpOperation( 6562): 	... 12 more
E/HttpOperation( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6562): 	at gde.c(Unknown Source)
E/HttpOperation( 6562): 	at gde.b(Unknown Source)
E/HttpOperation( 6562): 	at ihi.a(PG:19)
E/HttpOperation( 6562): 	... 14 more
,E/EsSyncAdapterService( 6562): Sync failure
E/EsSyncAdapterService( 6562): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6562): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6562): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6562): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6562): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6562): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6562): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6562): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6562): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6562): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6562): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6562): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6562): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6562): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6562): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6562): 	... 10 more
E/EsSyncAdapterService( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6562): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6562): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6562): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6562): 	... 12 more
E/EsSyncAdapterService( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6562): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6562): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6562): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6562): 	... 14 more
E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  887): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 155603, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  887): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  887): mCursor = null
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  887): waitForAlarm result :4
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6592): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6592): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6592): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 5
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  887): SIOP:: AP = 310, PST = 355, CUR = 300
,I/PowerManagerService(  887): [PWL] Off : 30s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 310, PST = 347, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :4
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  887): stay LED for fully charged
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1673): Vacuum at: now=1449681236146 tag=VacuumService
,I/GoogleURLConnFactory( 1673): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
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
,I/System.out( 1673): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1673): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1673): (HTTPLog)-Thread-196-805646524: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1673): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1673, getuid(): 10012
,I/qtaguid ( 1673): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1673, getuid(): 10012
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1673): No account for auth token provided
,E/SMD     (  285): DCD ON
,I/qtaguid ( 1673): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1673, getuid(): 10012
,D/Finsky  ( 6592): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6592): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6592): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1673): No account for auth token provided
,I/qtaguid ( 1673): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1673, getuid(): 10012
,W/Uploader( 1673): No account for auth token provided
,I/qtaguid ( 1673): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1673, getuid(): 10012
,W/Uploader( 1673): No account for auth token provided
,I/qtaguid ( 1673): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1673, getuid(): 10012
,W/Uploader( 1673):  no longer exists, so no auth token.
,I/qtaguid ( 1673): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1673, getuid(): 10012
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :8
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  887): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7348): Starting books sync, d
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1673): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7348): null auth token
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
D/PanelView( 1172): There is/are notification(s) 
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/PowerManagerService(  887): [PWL] Off : 50s ago
,I/PowerManagerService(  887): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  887): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  887): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=887, ws=WorkSource{10082}) (elapsedTime=496)
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6077492068574789848&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/SSRM:m  (  887): SIOP:: AP = 310, PST = 342, CUR = 300
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  285): DCD ON
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6077492068574789848&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6077492068574789848&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7348): Soft error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6077492068574789848&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7348): Sync error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6077492068574789848&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7348): Finished books sync
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  887): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 159143, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  887): Explicit concurrent mark sweep GC freed 43360(2MB) AllocSpace objects, 25(855KB) LOS objects, 30% free, 36MB/52MB, paused 1.788ms total 188.852ms
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecContentProvider2(  887): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  887): mCursor = null
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  285): DCD ON
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6562): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6562): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6562): 	at kfv.a(PG:65)
E/HttpOperation( 6562): 	at kff.u(PG:385)
E/HttpOperation( 6562): 	at kfb.a(PG:29)
E/HttpOperation( 6562): 	at kff.l(PG:132)
E/HttpOperation( 6562): 	at dsf.a(PG:807)
E/HttpOperation( 6562): 	at fhk.a(PG:1126)
E/HttpOperation( 6562): 	at fhk.a(PG:908)
E/HttpOperation( 6562): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6562): 	at ihi.a(PG:22)
E/HttpOperation( 6562): 	at kft.a(PG:91)
E/HttpOperation( 6562): 	at kfv.a(PG:62)
E/HttpOperation( 6562): 	... 8 more
E/HttpOperation( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6562): 	at gde.c(Unknown Source)
E/HttpOperation( 6562): 	at gde.b(Unknown Source)
E/HttpOperation( 6562): 	at ihi.a(PG:19)
E/HttpOperation( 6562): 	... 10 more
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6562): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6562): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6562): 	at kfv.a(PG:65)
E/HttpOperation( 6562): 	at kff.u(PG:385)
E/HttpOperation( 6562): 	at kfb.a(PG:29)
E/HttpOperation( 6562): 	at kff.l(PG:132)
E/HttpOperation( 6562): 	at ieo.a(PG:43)
E/HttpOperation( 6562): 	at iep.a(PG:93)
E/HttpOperation( 6562): 	at fhn.a(PG:59)
E/HttpOperation( 6562): 	at lex.a(PG:85)
E/HttpOperation( 6562): 	at lex.b(PG:132)
E/HttpOperation( 6562): 	at fhk.a(PG:1146)
E/HttpOperation( 6562): 	at fhk.a(PG:908)
E/HttpOperation( 6562): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6562): 	at ihi.a(PG:22)
E/HttpOperation( 6562): 	at kft.a(PG:91)
E/HttpOperation( 6562): 	at kfv.a(PG:62)
E/HttpOperation( 6562): 	... 12 more
E/HttpOperation( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6562): 	at gde.c(Unknown Source)
E/HttpOperation( 6562): 	at gde.b(Unknown Source)
E/HttpOperation( 6562): 	at ihi.a(PG:19)
E/HttpOperation( 6562): 	... 14 more
E/ExperimentLoader( 6562): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6562): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6562): 	at kfv.a(PG:65)
E/ExperimentLoader( 6562): 	at kff.u(PG:385)
E/ExperimentLoader( 6562): 	at kfb.a(PG:29)
E/ExperimentLoader( 6562): 	at kff.l(PG:132)
E/ExperimentLoader( 6562): 	at ieo.a(PG:43)
E/ExperimentLoader( 6562): 	at iep.a(PG:93)
E/ExperimentLoader( 6562): 	at fhn.a(PG:59)
E/ExperimentLoader( 6562): 	at lex.a(PG:85)
E/ExperimentLoader( 6562): 	at lex.b(PG:132)
E/ExperimentLoader( 6562): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6562): 	at fhk.a(PG:908)
E/ExperimentLoader( 6562): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6562): 	at ihi.a(PG:22)
E/ExperimentLoader( 6562): 	at kft.a(PG:91)
E/ExperimentLoader( 6562): 	at kfv.a(PG:62)
E/ExperimentLoader( 6562): 	... 12 more
E/ExperimentLoader( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6562): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6562): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6562): 	at ihi.a(PG:19)
E/ExperimentLoader( 6562): 	... 14 more
I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6562): [getaccountstatus] Unexpected exception
E/HttpOperation( 6562): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6562): 	at kfv.a(PG:65)
E/HttpOperation( 6562): 	at kff.u(PG:385)
E/HttpOperation( 6562): 	at kfb.a(PG:29)
E/HttpOperation( 6562): 	at ixd.a(PG:248)
E/HttpOperation( 6562): 	at ixd.b(PG:206)
E/HttpOperation( 6562): 	at ixd.a(PG:175)
E/HttpOperation( 6562): 	at fig.a(PG:78)
E/HttpOperation( 6562): 	at lex.a(PG:85)
E/HttpOperation( 6562): 	at lex.b(PG:132)
E/HttpOperation( 6562): 	at fhk.a(PG:1146)
E/HttpOperation( 6562): 	at fhk.a(PG:908)
E/HttpOperation( 6562): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6562): 	at ihi.a(PG:22)
E/HttpOperation( 6562): 	at kft.a(PG:91)
E/HttpOperation( 6562): 	at kfv.a(PG:62)
E/HttpOperation( 6562): 	... 12 more
E/HttpOperation( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6562): 	at gde.c(Unknown Source)
E/HttpOperation( 6562): 	at gde.b(Unknown Source)
E/HttpOperation( 6562): 	at ihi.a(PG:19)
E/HttpOperation( 6562): 	... 14 more
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/EsSyncAdapterService( 6562): Sync failure
E/EsSyncAdapterService( 6562): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6562): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6562): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6562): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6562): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6562): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6562): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6562): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6562): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6562): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6562): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6562): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6562): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6562): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6562): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6562): 	... 10 more
E/EsSyncAdapterService( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6562): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6562): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6562): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6562): 	... 12 more
E/EsSyncAdapterService( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6562): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6562): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6562): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6562): 	... 14 more
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,D/SyncManager(  887): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 187436, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  887): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  887): mCursor = null
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 6
,D/SSRM:m  (  887): SIOP:: AP = 310, PST = 333, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON,
,E/SMD     (  285): DCD ON,
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 300, PST = 323, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  887): [PWL] Off : 75s ago
,E/SMD     (  285): DCD ON
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :4
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  887): SIOP:: AP = 300, PST = 316, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/Watchdog(  887): !@Sync 7
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 300, PST = 312, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  285): DCD ON
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  887): SIOP:: AP = 300, PST = 309, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  887): [PWL] Off : 105s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :8
,V/AlarmManager(  887): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7348): Starting books sync, d
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2713369382079783853&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  887): SIOP:: AP = 300, PST = 306, CUR = 300
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  285): DCD ON
,I/art     ( 1673): Explicit concurrent mark sweep GC freed 50466(3MB) AllocSpace objects, 70(4MB) LOS objects, 40% free, 18MB/30MB, paused 957us total 66.967ms
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1673): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2713369382079783853&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2713369382079783853&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/BooksSync( 7348): Soft error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2713369382079783853&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7348): Sync error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2713369382079783853&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7348): Finished books sync
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  887): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 220271, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  887): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  887): mCursor = null
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 8
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 300, PST = 304, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,D/BatteryService(  887): stay LED for fully charged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  887): SIOP:: AP = 300, PST = 303, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :4
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  887): stay LED for fully charged
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/PowerManagerService(  887): [PWL] Off : 140s ago
,I/PowerManagerService(  887): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  887): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  887): [PWL]       PARTIAL_WAKE_LOCK              'SyncManagerHandleSyncAlarm' (uid=1000, pid=887, ws=null) (elapsedTime=96)
,I/PowerManagerService(  887): [PWL]       PARTIAL_WAKE_LOCK              'SyncLoopWakeLock' (uid=1000, pid=887, ws=null) (elapsedTime=73)
I/PowerManagerService(  887): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.plus.content.EsProvider/com.google/eM_ADDR' (uid=1000, pid=887, ws=WorkSource{10135}) (elapsedTime=55)
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 1673): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
E/HttpOperation( 6562): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6562): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6562): 	at kfv.a(PG:65)
E/HttpOperation( 6562): 	at kff.u(PG:385)
E/HttpOperation( 6562): 	at kfb.a(PG:29)
E/HttpOperation( 6562): 	at kff.l(PG:132)
E/HttpOperation( 6562): 	at dsf.a(PG:807)
E/HttpOperation( 6562): 	at fhk.a(PG:1126)
E/HttpOperation( 6562): 	at fhk.a(PG:908)
E/HttpOperation( 6562): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6562): 	at ihi.a(PG:22)
E/HttpOperation( 6562): 	at kft.a(PG:91)
E/HttpOperation( 6562): 	at kfv.a(PG:62)
E/HttpOperation( 6562): 	... 8 more
E/HttpOperation( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6562): 	at gde.c(Unknown Source)
E/HttpOperation( 6562): 	at gde.b(Unknown Source)
E/HttpOperation( 6562): 	at ihi.a(PG:19)
E/HttpOperation( 6562): 	... 10 more
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6562): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6562): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6562): 	at kfv.a(PG:65)
E/HttpOperation( 6562): 	at kff.u(PG:385)
E/HttpOperation( 6562): 	at kfb.a(PG:29)
E/HttpOperation( 6562): 	at kff.l(PG:132)
E/HttpOperation( 6562): 	at ieo.a(PG:43)
E/HttpOperation( 6562): 	at iep.a(PG:93)
E/HttpOperation( 6562): 	at fhn.a(PG:59)
E/HttpOperation( 6562): 	at lex.a(PG:85)
E/HttpOperation( 6562): 	at lex.b(PG:132)
E/HttpOperation( 6562): 	at fhk.a(PG:1146)
E/HttpOperation( 6562): 	at fhk.a(PG:908)
E/HttpOperation( 6562): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6562): 	at ihi.a(PG:22)
E/HttpOperation( 6562): 	at kft.a(PG:91)
E/HttpOperation( 6562): 	at kfv.a(PG:62)
E/HttpOperation( 6562): 	... 12 more
E/HttpOperation( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6562): 	at gde.c(Unknown Source)
E/HttpOperation( 6562): 	at gde.b(Unknown Source)
E/HttpOperation( 6562): 	at ihi.a(PG:19)
E/HttpOperation( 6562): 	... 14 more
,E/ExperimentLoader( 6562): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6562): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6562): 	at kfv.a(PG:65)
E/ExperimentLoader( 6562): 	at kff.u(PG:385)
E/ExperimentLoader( 6562): 	at kfb.a(PG:29)
E/ExperimentLoader( 6562): 	at kff.l(PG:132)
E/ExperimentLoader( 6562): 	at ieo.a(PG:43)
E/ExperimentLoader( 6562): 	at iep.a(PG:93)
E/ExperimentLoader( 6562): 	at fhn.a(PG:59)
E/ExperimentLoader( 6562): 	at lex.a(PG:85)
E/ExperimentLoader( 6562): 	at lex.b(PG:132)
E/ExperimentLoader( 6562): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6562): 	at fhk.a(PG:908)
E/ExperimentLoader( 6562): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6562): 	at ihi.a(PG:22)
E/ExperimentLoader( 6562): 	at kft.a(PG:91)
E/ExperimentLoader( 6562): 	at kfv.a(PG:62)
E/ExperimentLoader( 6562): 	... 12 more
E/ExperimentLoader( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6562): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6562): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6562): 	at ihi.a(PG:19)
E/ExperimentLoader( 6562): 	... 14 more
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6562): [getaccountstatus] Unexpected exception
E/HttpOperation( 6562): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6562): 	at kfv.a(PG:65)
E/HttpOperation( 6562): 	at kff.u(PG:385)
E/HttpOperation( 6562): 	at kfb.a(PG:29)
E/HttpOperation( 6562): 	at ixd.a(PG:248)
E/HttpOperation( 6562): 	at ixd.b(PG:206)
E/HttpOperation( 6562): 	at ixd.a(PG:175)
E/HttpOperation( 6562): 	at fig.a(PG:78)
E/HttpOperation( 6562): 	at lex.a(PG:85)
E/HttpOperation( 6562): 	at lex.b(PG:132)
E/HttpOperation( 6562): 	at fhk.a(PG:1146)
E/HttpOperation( 6562): 	at fhk.a(PG:908)
E/HttpOperation( 6562): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6562): 	at ihi.a(PG:22)
E/HttpOperation( 6562): 	at kft.a(PG:91)
E/HttpOperation( 6562): 	at kfv.a(PG:62)
E/HttpOperation( 6562): 	... 12 more
E/HttpOperation( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6562): 	at gde.c(Unknown Source)
E/HttpOperation( 6562): 	at gde.b(Unknown Source)
E/HttpOperation( 6562): 	at ihi.a(PG:19)
E/HttpOperation( 6562): 	... 14 more
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/EsSyncAdapterService( 6562): Sync failure
E/EsSyncAdapterService( 6562): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6562): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6562): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6562): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6562): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6562): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6562): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6562): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6562): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6562): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6562): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6562): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6562): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6562): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6562): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6562): 	... 10 more
E/EsSyncAdapterService( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6562): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6562): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6562): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6562): 	... 12 more
E/EsSyncAdapterService( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6562): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6562): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6562): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6562): 	... 14 more
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 301, CUR = 300
D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
D/SyncManager(  887): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 253334, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  887): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  887): mCursor = null
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 9
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 299, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 297, CUR = 300
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :8
,V/AlarmManager(  887): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): stay LED for fully charged
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 296, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/TimaService(  887): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  887): TimaServiceHandler.handleMessage what =1
,D/TimaService(  887): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  887): initializing...
,I/TLC_TIMA_PKM_initialize(  887): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  887): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  887): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  887): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  887): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  887): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  887): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  887): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  887): App is not loaded in QSEE
,D/QSEECOMAPI: (  887): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  887): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  887): Trustlet response is completed
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  887): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  887): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  887): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  887): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/PowerManagerService(  887): [PWL] Off : 180s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 300, PST = 296, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  887): waitForAlarm result :4
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8345): MountEmulatedStorage()
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,I/ActivityManager(  887): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8345 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 8345): v2
,I/libpersona( 8345): KNOX_SDCARD checking this for 10081
I/libpersona( 8345): KNOX_SDCARD not a persona
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,I/SELinux ( 8345): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8345): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8345): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,I/art     (  317): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 420us total 54.455ms
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 389us total 12.496ms
,D/TimaKeyStoreProvider( 8345): TimaSignature is unavailable
,D/ActivityThread( 8345): Added TimaKeyStore provider
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 1.885ms total 47.864ms
,D/ResourcesManager( 8345): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  887): Killing 7020:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,W/libprocessgroup(  887): failed to open /acct/uid_10166/pid_7020/cgroup.procs: No such file or directory
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :4
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7348): Starting books sync, d
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2836432814924502116&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2836432814924502116&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2836432814924502116&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/BooksSync( 7348): Soft error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2836432814924502116&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7348): Sync error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2836432814924502116&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): Headers suppressed
E/BooksSync( 7348): 
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7348): Finished books sync
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  887): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 310493, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/art     (  887): Explicit concurrent mark sweep GC freed 58136(3MB) AllocSpace objects, 62(1772KB) LOS objects, 30% free, 36MB/52MB, paused 2.197ms total 211.994ms
,D/SecContentProvider2(  887): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  887): mCursor = null
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 11
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 293, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 292, CUR = 300
,D/ResourcesManager( 1673): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/PlayEventLogger( 6592): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6592): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6592): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6592): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6592): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6592): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6592): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/System  ( 6592): Ignoring header User-Agent because its value was null.
,I/System.out( 6592): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6592): (HTTPLog)-Static: isShipBuild true
,I/System.out( 6592): (HTTPLog)-Thread-1083-422243040: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  887): [PWL] Off : 225s ago
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :8
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  887): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): stay LED for fully charged
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  285): DCD ON
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 12
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 291, CUR = 300
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :4
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  887): stay LED for fully charged
D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6562): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6562): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6562): 	at kfv.a(PG:65)
E/HttpOperation( 6562): 	at kff.u(PG:385)
E/HttpOperation( 6562): 	at kfb.a(PG:29)
E/HttpOperation( 6562): 	at kff.l(PG:132)
E/HttpOperation( 6562): 	at dsf.a(PG:807)
E/HttpOperation( 6562): 	at fhk.a(PG:1126)
E/HttpOperation( 6562): 	at fhk.a(PG:908)
E/HttpOperation( 6562): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6562): 	at ihi.a(PG:22)
E/HttpOperation( 6562): 	at kft.a(PG:91)
E/HttpOperation( 6562): 	at kfv.a(PG:62)
E/HttpOperation( 6562): 	... 8 more
E/HttpOperation( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6562): 	at gde.c(Unknown Source)
E/HttpOperation( 6562): 	at gde.b(Unknown Source)
E/HttpOperation( 6562): 	at ihi.a(PG:19)
E/HttpOperation( 6562): 	... 10 more
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6562): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6562): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6562): 	at kfv.a(PG:65)
E/HttpOperation( 6562): 	at kff.u(PG:385)
E/HttpOperation( 6562): 	at kfb.a(PG:29)
E/HttpOperation( 6562): 	at kff.l(PG:132)
E/HttpOperation( 6562): 	at ieo.a(PG:43)
E/HttpOperation( 6562): 	at iep.a(PG:93)
E/HttpOperation( 6562): 	at fhn.a(PG:59)
E/HttpOperation( 6562): 	at lex.a(PG:85)
E/HttpOperation( 6562): 	at lex.b(PG:132)
E/HttpOperation( 6562): 	at fhk.a(PG:1146)
E/HttpOperation( 6562): 	at fhk.a(PG:908)
E/HttpOperation( 6562): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6562): 	at ihi.a(PG:22)
E/HttpOperation( 6562): 	at kft.a(PG:91)
E/HttpOperation( 6562): 	at kfv.a(PG:62)
E/HttpOperation( 6562): 	... 12 more
E/HttpOperation( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6562): 	at gde.c(Unknown Source)
E/HttpOperation( 6562): 	at gde.b(Unknown Source)
E/HttpOperation( 6562): 	at ihi.a(PG:19)
E/HttpOperation( 6562): 	... 14 more
,E/ExperimentLoader( 6562): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6562): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6562): 	at kfv.a(PG:65)
E/ExperimentLoader( 6562): 	at kff.u(PG:385)
E/ExperimentLoader( 6562): 	at kfb.a(PG:29)
E/ExperimentLoader( 6562): 	at kff.l(PG:132)
E/ExperimentLoader( 6562): 	at ieo.a(PG:43)
E/ExperimentLoader( 6562): 	at iep.a(PG:93)
E/ExperimentLoader( 6562): 	at fhn.a(PG:59)
E/ExperimentLoader( 6562): 	at lex.a(PG:85)
E/ExperimentLoader( 6562): 	at lex.b(PG:132)
E/ExperimentLoader( 6562): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6562): 	at fhk.a(PG:908)
E/ExperimentLoader( 6562): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6562): 	at ihi.a(PG:22)
E/ExperimentLoader( 6562): 	at kft.a(PG:91)
E/ExperimentLoader( 6562): 	at kfv.a(PG:62)
E/ExperimentLoader( 6562): 	... 12 more
E/ExperimentLoader( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6562): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6562): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6562): 	at ihi.a(PG:19)
E/ExperimentLoader( 6562): 	... 14 more
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6562): [getaccountstatus] Unexpected exception
E/HttpOperation( 6562): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6562): 	at kfv.a(PG:65)
E/HttpOperation( 6562): 	at kff.u(PG:385)
E/HttpOperation( 6562): 	at kfb.a(PG:29)
E/HttpOperation( 6562): 	at ixd.a(PG:248)
E/HttpOperation( 6562): 	at ixd.b(PG:206)
E/HttpOperation( 6562): 	at ixd.a(PG:175)
E/HttpOperation( 6562): 	at fig.a(PG:78)
E/HttpOperation( 6562): 	at lex.a(PG:85)
E/HttpOperation( 6562): 	at lex.b(PG:132)
E/HttpOperation( 6562): 	at fhk.a(PG:1146)
E/HttpOperation( 6562): 	at fhk.a(PG:908)
E/HttpOperation( 6562): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6562): 	at ihi.a(PG:22)
E/HttpOperation( 6562): 	at kft.a(PG:91)
E/HttpOperation( 6562): 	at kfv.a(PG:62)
E/HttpOperation( 6562): 	... 12 more
E/HttpOperation( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6562): 	at gde.c(Unknown Source)
E/HttpOperation( 6562): 	at gde.b(Unknown Source)
E/HttpOperation( 6562): 	at ihi.a(PG:19)
E/HttpOperation( 6562): 	... 14 more
,E/EsSyncAdapterService( 6562): Sync failure
E/EsSyncAdapterService( 6562): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6562): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6562): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6562): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6562): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6562): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6562): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6562): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6562): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6562): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6562): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6562): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6562): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6562): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6562): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6562): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6562): 	... 10 more
E/EsSyncAdapterService( 6562): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6562): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6562): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6562): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6562): 	... 12 more
E/EsSyncAdapterService( 6562): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6562): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6562): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6562): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6562): 	... 14 more
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  887): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 401227, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2855): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  887): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  887): mCursor = null
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 13
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 291, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/PowerManagerService(  887): [PWL] Off : 275s ago
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  887): stay LED for fully charged
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 14
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  887): waitForAlarm result :4
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  887): stay LED for fully charged
D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7348): Starting books sync, d
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,I/qtaguid ( 7348): Untagging socket 34
,W/ApiaryClient( 7348): Error response from books API: {
W/ApiaryClient( 7348):  "error": {
W/ApiaryClient( 7348):   "errors": [
W/ApiaryClient( 7348):    {
W/ApiaryClient( 7348):     "domain": "global",
W/ApiaryClient( 7348):     "reason": "required",
W/ApiaryClient( 7348):     "message": "Login Required",
W/ApiaryClient( 7348):     "locationType": "header",
W/ApiaryClient( 7348):     "location": "Authorization"
W/ApiaryClient( 7348):    }
W/ApiaryClient( 7348):   ],
W/ApiaryClient( 7348):   "code": 401,
W/ApiaryClient( 7348):   "message": "Login Required"
W/ApiaryClient( 7348):  }
W/ApiaryClient( 7348): }
,W/ApiaryClient( 7348): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7348): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8636562706184667004&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
,D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1673): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,I/jxcore-log( 7421): Toggling radios to false
I/jxcore-log( 7421): 
,D/BluetoothAdapter( 7421): disable()
,D/SettingsProvider(  887): name = bluetooth_on
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
,D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,I/WifiManager( 7421): packageName : com.test.thalitest
,D/SecContentProvider(  887): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  887): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  887): mCursor = null
,D/WifiService(  887): setWifiEnabled: false pid=7421, uid=10367
,E/WifiService(  887): Invoking mWifiStateMachine.setWifiEnabled
D/SettingsProvider(  887): name = wifi_on
,D/BluetoothAdapterState( 3246): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 3246): Setting state to 13
I/BluetoothAdapterState( 3246): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 3246): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3246): updateAdapterState state is 13
,D/BluetoothAdapterService( 3246): Autoconnection is available 
,D/BluetoothAdapterService( 3246): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 3246): terminating service from this receiver
,I/BluetoothPbapService( 3246): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothSocket( 3246): close() in, this: android.bluetooth.BluetoothSocket@21797cdc, channel: 19, state: LISTENING
D/BluetoothSocket( 3246): close() this: android.bluetooth.BluetoothSocket@21797cdc, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b4c4944, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@32ed61e5mSocket: android.net.LocalSocket@1f04a4ba impl:android.net.LocalSocketImpl@106ff6b fd:FileDescriptor[72]
,D/BluetoothSocket( 3246): Closing mSocket: android.net.LocalSocket@1f04a4ba impl:android.net.LocalSocketImpl@106ff6b fd:FileDescriptor[72]
,W/InputMethodManagerService(  887): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  887): [BT Setting State] State =13
,D/BluetoothTile( 1172): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/STATUSBAR-QSTileView( 1172): onStateChanged: Bluetooth
,V/BitmapFactory( 1172): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_bluetooth_dim.png
,E/WifiStateMachine(  887): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1274): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1274): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1274): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 1274): Scan requested (ret=0) - scan timeout 30 seconds
,I/jxcore-log( 7421): Radios toggled
I/jxcore-log( 7421): 
,E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  887): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  887): handleNetworkDisconnect "NG700" nid=0
,E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  887): do suspend true
V/BluetoothEventManager( 1306): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/WifiP2pService(  887): InactiveState{ what=143375 }
D/WifiP2pService(  887): P2pEnabledState{ what=143375 }
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/BluetoothAdapterProperties( 3246): onBluetoothDisable()
,D/SecContentProvider(  887): uri = 3 selection = isDiscoverableEnabled
,I/SamsungIME( 1862): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/bt_vendor( 3246): op for 7
,W/GLSActivity( 1673): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1673): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1673): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1673): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1673): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/bt_upio ( 3246): proc btwrite assertion
,I/BluetoothAdapterState( 3246): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3246): Scan Mode:20
,D/BluetoothAdapterState( 3246): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 3246): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 3246): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/bt-btif ( 3246): cmd socket is not created
,E/BtOppRfcommListener( 3246): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btm  ( 3246): btm_ble_start_auto_conn start : 0, 0
,W/bt-btif ( 3246): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/btif_config_util( 3246): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 3246): L2CAP - PSM: 0x0019 not found for deregistration
V/NativeCrypto( 1673): Read error: ssl=0xad342600: I/O error during system call, Connection timed out
W/bt-l2cap( 3246): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 3246): L2CAP - PSM: 0x001b not found for deregistration
D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  887): updateNetworkInfo()
D/bt_vendor( 3246): op for 7
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/bt_upio ( 3246): BT_WAKE is asserted already
,E/ConnectivityService(  887): updateNetworkInfo()
D/ConnectivityService(  887): ignoring duplicate network state non-change
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 2
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/WifiTrafficPoller(  887): evaluateTrafficStatsPolling
,I/CLocInfoService(  887): External Intent Received android.net.wifi.STATE_CHANGE
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/StatusBar.NetworkController( 1172): applyOpen
V/NativeCrypto( 1673): SSL shutdown failed: ssl=0xad342600: I/O error during system call, Broken pipe
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,E/BooksAccountManager( 7348): Authentication error
E/BooksAccountManager( 7348): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7348): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7348): null auth token
D/StatusBar.NetworkController( 1172): applyOpen
,I/qtaguid ( 7348): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7348, getuid(): 10082
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/BluetoothSocket( 3246): close() in, this: android.bluetooth.BluetoothSocket@98f8ac8, channel: 5, state: LISTENING
D/BluetoothSocket( 3246): close() this: android.bluetooth.BluetoothSocket@98f8ac8, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c661a2d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2d173761mSocket: android.net.LocalSocket@3bc85286 impl:android.net.LocalSocketImpl@17142747 fd:FileDescriptor[74]
,D/BluetoothSocket( 3246): Closing mSocket: android.net.LocalSocket@3bc85286 impl:android.net.LocalSocketImpl@17142747 fd:FileDescriptor[74]
I/BtOppRfcommListener( 3246): stopping Accept Thread
D/BluetoothSocket( 3246): close() in, this: android.bluetooth.BluetoothSocket@1f768b74, channel: 12, state: LISTENING
,D/BluetoothSocket( 3246): close() this: android.bluetooth.BluetoothSocket@1f768b74, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39ffdd4f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@13aee89dmSocket: android.net.LocalSocket@32c71112 impl:android.net.LocalSocketImpl@be1f0e3 fd:FileDescriptor[78]
D/BluetoothSocket( 3246): Closing mSocket: android.net.LocalSocket@32c71112 impl:android.net.LocalSocketImpl@be1f0e3 fd:FileDescriptor[78]
I/BtOppRfcommListener( 3246): BluetoothSocket listen thread finished
E/WifiStateMachine(  887): scanCount==0 - aborting
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,E/WifiStateMachine(  887): [1,449,681,518,817 ms] noteScanEnd no scan source
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/WifiP2pService(  887): InactiveState{ what=131204 }
D/WifiP2pService(  887): P2pEnabledState{ what=131204 }
,E/ActivityThread( 3246): Service com.samsung.ble.BleAutoConnectService has leaked IntentReceiver com.samsung.ble.BleAutoConnectService$4@b46c17b that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3246): android.app.IntentReceiverLeaked: Service com.samsung.ble.BleAutoConnectService has leaked IntentReceiver com.samsung.ble.BleAutoConnectService$4@b46c17b that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3246): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:960)
E/ActivityThread( 3246): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:761)
E/ActivityThread( 3246): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1945)
E/ActivityThread( 3246): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1925)
E/ActivityThread( 3246): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1919)
E/ActivityThread( 3246): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
E/ActivityThread( 3246): 	at com.samsung.ble.BleAutoConnectService.onCreate(BleAutoConnectService.java:139)
E/ActivityThread( 3246): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 3246): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 3246): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 3246): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3246): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3246): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 3246): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3246): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3246): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 3246): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  887): notifyType LOST for NetworkAgentInfo [WIFI () - 503]
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  887): calling update connectivity
D/ConnectivityService(  887):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiNetworkAgent(  887): NetworkAgent: NetworkAgent channel lost
D/EntConnectivity(  887): Not allowed due to - mEnabled false
D/ConnectivityService(  887):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  887): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  887): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Nat464Xlat(  887): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524292
D/ConnectivityService(  887): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  887): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  887): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  887): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=false
D/TelephonyNetworkFactory( 1465): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): sending p2p connection changed broadcast: FAILED
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Disconnected - quitting
D/BluetoothPbap( 1306): Proxy object disconnected
D/PbapServerProfile( 1306): Bluetooth service disconnected
W/ApiaryClient( 7348): errCount = 2: com.google.android.apps.books.net.HttpHelper$OfflineIoException: java.net.UnknownHostException: URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8636562706184667004&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7348): Headers suppressed
D/WifiScanningService(  887): SCAN_AVAILABLE : 1
D/RttService(  887): SCAN_AVAILABLE : 1
D/WifiScanningService(  887): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  887): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  887): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
E/ConnectivityService(  887): updateNetworkInfo()
D/ConnectivityService(  887): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiDisplayController(  887): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  887): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  887): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  887): getSBEnabled() enabled =false
D/WifiDisplayAdapter(  887): onP2pDisconnected
D/SmartBondingService(  887): getSBEnabled() enabled =false
E/BooksSync( 7348): Soft error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$OfflineIoException: com.google.android.apps.books.net.HttpHelper$OfflineIoException: Device offline, skipping https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8636562706184667004&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.shouldSkipRetry(HttpHelper.java:88)
E/BooksSync( 7348): Sync error
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper$OfflineIoException: com.google.android.apps.books.net.HttpHelper$OfflineIoException: Device offline, skipping https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8636562706184667004&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7348): com.google.android.apps.books.net.HttpHelper.shouldSkipRetry(HttpHelper.java:88)
D/SmartBondingService(  887): getSBEnabled() enabled =false
V/NetworkStats(  887): updateIfacesLocked()
V/NetworkStats(  887): performPollLocked(flags=0x1)
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
I/BooksSync( 7348): Finished books sync
D/NetworkStatsFactory(  887): UpdateStatsForKnox
D/IpRemoteDisplayController(  887): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  887): WfdBridgeServer is already null
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  887): getNetworkEnabled : wifi : true mobile : true
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
V/NetworkStats(  887): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
V/NetworkStats(  887): performPollLocked() took 7ms
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
D/WifiP2pService(  887): sending p2p connection changed broadcast: DISCONNECTED
E/ConnectivityService(  887): updateNetworkInfo()
D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/ConnectivityService(  887): ignoring duplicate network state non-change
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/WifiP2pService(  887): P2pDisablingState
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/WifiP2pService(  887): P2pDisablingState{ what=147458 }
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/WifiP2pService(  887): p2p socket connection lost
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/WifiP2pService(  887): P2pDisabledState
D/DockEventReceiver( 1306): finishStartingService: stopping service
,E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - enter - invokeEnterMethods
D/SyncManager(  887): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 461301, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  887): do suspend true
D/BluetoothNotiBroadcastReceiver( 1306): onReceive
E/WifiStateMachine(  887): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController(  887): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  887): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  887): disconnect
D/WifiDisplayController(  887): updateConnection
D/WifiDisplayController(  887): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  887): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiP2pService(  887): P2pDisabledState{ what=143375 }
D/WifiP2pService(  887): DefaultState{ what=143375 }
D/CommandListener(  278): Clearing all IP addresses on wlan0
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
D/ResourcesManager( 2855): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/WifiDisplayController(  887): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/WifiDisplayAdapter(  887): onP2pDisconnected
D/IpRemoteDisplayController(  887): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  887): WfdBridgeServer is already null
E/WifiStateMachine(  887): stopping supplicant
I/wpa_supplicant( 1274): p2p0: State: DISCONNECTED -> DISCONNECTED
I/WifiTrafficPoller(  887): evaluateTrafficStatsPolling
E/SMD     (  285): DCD ON
E/WifiStateMachine(  887): setWifiState: disabling
I/CLocInfoService(  887): External Intent Received android.net.wifi.STATE_CHANGE
D/AllShareCastTile( 1172): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter(  887): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1172): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/SmartBondingService(  887): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation(  887): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/SmartBondingService(  887): getNetworkEnabled : wifi : false mobile : true
,D/SecContentProvider2(  887): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  887): mCursor = null
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/STATUSBAR-WifiQuickSettingButton( 1172): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1172): Wifi onReceive(0)
D/STATUSBAR-QSTileView( 1172): onStateChanged: Wi-Fi
,V/BitmapFactory( 1172): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_wifi_dim.png
,D/HotspotTile( 1172): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/WifiCredService( 1306): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1172): onReceive : 0, 0
,I/wpa_supplicant( 1274): Blacklist: Clear (all) 
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/AuthorizationBluetoothService( 1673): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 1274): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 1274): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1274): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1274): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/ResourcesManager( 2855): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  887): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  887): mCursor = null
,I/Hs20UtilService( 1306): Starting #12
,I/Hs20UtilService( 1306): Message received 5007
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/bt_vendor( 3246): op for 6
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_userial( 3246): RX termination
W/bt_userial( 3246): select_read return size <=0:-1, exiting userial_read_thread
W/bt-l2cap( 3246): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3246): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3246): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3246): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3246): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3246): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3246): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3246): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3246): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 3246): ag scb idx 1 not allocated
W/bt-btif ( 3246): ag scb idx 2 not allocated
E/bt-btif ( 3246): BTA AG is already disabled, ignoring ...
D/bt_userial( 3246): Leaving userial_read_thread()
D/bt_userial( 3246): userial_close_reader Joined userial reader thread: 0
D/bt_vendor( 3246): op for 9
D/bt_hwcfg( 3246): hw_epilog_process
,D/bt_vendor( 3246): op for 4
I/bt_userial_vendor( 3246): device fd = 65 close
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
,D/bt_vendor( 3246): op for 0
,D/bt_upio ( 3246): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 3246): is_emulator_context : 0
D/bt_upio ( 3246): is_rfkill_disabled ? [0]
,D/bt_vendor( 3246): cleanup
,I/GKI_LINUX( 3246): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 3246): GKI_exit_task 0 done
,I/GKI_LINUX( 3246): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3246): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 3246): isSecureModeOn:false
,D/BluetoothAdapterService( 3246): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 3246): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 3246): Not skipping com.android.bluetooth.gatt.GattService
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/BluetoothAdapterService( 3246): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 3246): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.DebugUtils( 3246): handleDebugAction() action=null
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/BtGatt.GattService( 3246): Received stop request...Stopping profile...
D/BtGatt.GattService( 3246): stop()
,D/BtGatt.AdvertiseManager( 3246): advertise clients cleared
,D/BluetoothAdapterService( 3246): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e442fab
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
W/BluetoothAdapterService( 3246): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
W/BluetoothAdapterService( 3246): Not skipping com.android.bluetooth.a2dp.A2dpService
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
,I/wpa_supplicant( 1274): Blacklist: Clear (all) 
,W/BluetoothAdapterService( 3246): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3246): Not skipping com.android.bluetooth.hid.HidService
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8516): MountEmulatedStorage()
E/Zygote  ( 8516): v2
I/libpersona( 8516): KNOX_SDCARD checking this for 10075
I/libpersona( 8516): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8516 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8516): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/BluetoothAdapterService( 3246): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3246): Not skipping com.android.bluetooth.hdp.HealthService
,I/SELinux ( 8516): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/BluetoothAdapterService( 3246): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,E/SELinux ( 8516): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/BluetoothAdapterService( 3246): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3246): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3246): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3246): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 3246): Not skipping com.broadcom.bt.service.sap.SapService
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,W/BluetoothAdapterService( 3246): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 3246): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 3246): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 3246): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 3246): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 3246): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 3246): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 3246): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 3246): Stopping profile services that were post enabled
E/BluetoothAdapterService(507785131)( 3246): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/HeadsetService( 3246): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3246): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e442fab
,D/AudioService(  887): onServiceDisconnected: Bluetooth profile: 1
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/A2dpService( 3246): Received stop request...Stopping profile...
,D/HeadsetProfile( 1306): Bluetooth service disconnected
V/Avrcp   ( 3246): doQuit
,D/Avrcp   ( 3246): Unregistering previous receiver
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/BluetoothAdapterService( 3246): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e442fab
,D/BluetoothA2dp(  887): Proxy object disconnected
D/AudioService(  887): onServiceDisconnected: Bluetooth profile: 2
D/A2dpStateMachine( 3246): Exit Disconnected: -1
,D/BluetoothA2dp( 1306): Proxy object disconnected
D/A2dpProfile( 1306): Bluetooth service disconnected
,D/HidService( 3246): Received stop request...Stopping profile...
D/HidService( 3246): Stopping Bluetooth HidService
D/BluetoothAdapterService( 3246): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e442fab
,D/BluetoothA2dp( 3540): Proxy object disconnected
D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/HealthService( 3246): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3246): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e442fab
,D/BluetoothInputDevice( 1306): Proxy object disconnected
D/HidProfile( 1306): Bluetooth service disconnected
,D/PanService( 3246): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3246): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e442fab
,D/BluetoothMapService( 3246): Received stop request...Stopping profile...
D/BluetoothPan(  887): BluetoothPAN Proxy object disconnected
,D/BluetoothPan( 1306): BluetoothPAN Proxy object disconnected
D/PanProfile( 1306): Bluetooth service disconnected
,D/BluetoothAdapterService( 3246): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e442fab
,D/BluetoothMap( 1306): Proxy object disconnected
D/MapProfile( 1306): Bluetooth service disconnected
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/SapService( 3246): Received stop request...Stopping profile...
D/SapService( 3246): Stopping Bluetooth SapService
D/BluetoothAdapterService( 3246): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e442fab
,D/Bluetoothsap( 1306): BluetoothSAP Proxy object disconnected
,E/BluetoothAdapterService(507785131)( 3246): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,D/SapProfile( 1306): Bluetooth service disconnected
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 3246): Profile still running: com.android.bluetooth.hid.HidService
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,E/Watchdog(  887): !@Sync 15
,W/BluetoothHeadsetServiceJni( 3246): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 3246): Cleaning up Bluetooth Handsfree callback object
E/BluetoothAdapterService(507785131)( 3246): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,D/BluetoothAdapterService( 3246): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 3246): Proxy object disconnected
D/BluetoothAdapterService( 3246): Bluetooth A2dp source service disconnected
,I/GKI_LINUX( 3246): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3246): GKI_exit_task 2 done
I/GKI_LINUX( 3246): GKI_shutdown(): task [A2DP-MEDIA] terminated
,V/Avrcp   ( 3246): cleanup
E/BluetoothAdapterService(507785131)( 3246): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3246): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHidServiceJni( 3246): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3246): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 3246): Cleaning up Bluetooth GID callback object
E/BluetoothAdapterService(507785131)( 3246): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3246): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 3246): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3246): Cleaning up Bluetooth Health object
,E/BluetoothAdapterService(507785131)( 3246): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3246): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 3246): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3246): Cleaning up Bluetooth PAN callback object
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,E/BluetoothAdapterService(507785131)( 3246): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3246): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 3246): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(507785131)( 3246): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,D/BluetoothAdapterState( 3246): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3246): Setting state to 10
D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,I/BluetoothAdapterState( 3246): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3246): Bluetooth PBAP supproted is true
W/BluetoothSAPServiceJni( 3246): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 3246): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService( 3246): updateAdapterState state is 10
,D/BluetoothAdapterService( 3246): Autoconnection is available 
D/BluetoothAdapterService( 3246): updateAdapterState prevState = 13newState = 10
,I/BluetoothAdapterState( 3246): Entering OffState
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/BluetoothInputDevice( 1306): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/BluetoothMap( 1306): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1306): onBluetoothStateChange: up=false
D/Bluetoothsap( 1306): Unbinding service...
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
D/BluetoothA2dp( 3540): onBluetoothStateChange: up=false
,D/TimaKeyStoreProvider( 8516): TimaSignature is unavailable
,D/ActivityThread( 8516): Added TimaKeyStore provider
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/BluetoothA2dp( 1306): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/BluetoothA2dp( 3246): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 1465): FileWriteThread : threadType = 3
,D/BluetoothPbap( 1306): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  887): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  887): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/BluetoothManagerService(  887): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/ResourcesManager( 8516): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,I/GKI_LINUX( 3246): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3246): GKI_exit_task 1 done
W/InputMethodManagerService(  887): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  887): [BT Setting State] State =10
I/InputMethodManagerService(  887): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,I/wpa_supplicant( 1274): wlan0: CTRL-EVENT-TERMINATING 
,E/WifiStateMachine(  887): Supplicant connection lost
,I/GKI_LINUX( 3246): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 3246): cleanupNative: return from cleanup
,D/Tethering(  887): InitialState.processMessage what=4
,E/Tethering(  887): No numeric data
,I/art     ( 3246): System.exit called, status: 0
I/AndroidRuntime( 3246): VM exiting with result code 0, cleanup skipped.
,D/BluetoothAdapter( 1172): 132402266: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1172): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapter( 1172): 132402266: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1172): 132402266: getState() :  mService = null. Returning STATE_OFF
,D/Tethering(  887): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  887): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-HAL(  887): callSECApiBoolean - ID [21]
E/WifiStateMachine(  887): setWifiState: disabled
,D/STATUSBAR-QSTileView( 1172): onStateChanged: Bluetooth
,V/NetworkStats(  887): performPollLocked(flags=0x1)
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
,V/BitmapFactory( 1172): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_bluetooth_off.png
D/NetworkStatsFactory(  887): UpdateStatsForKnox
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SamsungIME( 1862): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/SLocation(  887): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
D/SmartBondingService(  887): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/SmartBondingService(  887): getNetworkEnabled : wifi : false mobile : true
,D/HotspotTile( 1172): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1172): updateTetherState():false, false
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1172): Wifi onReceive(1)
W/Settings( 2186): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/NetworkStats(  887): performPollLocked() took 20ms
,D/HotspotTile( 1172): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1172): onReceive : 1, 0
D/STATUSBAR-QSTileView( 1172): onStateChanged: Wi-Fi
,D/NtpTrustedTime(  887): currentTimeMillis() cache hit
,V/BitmapFactory( 1172): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_wifi_off.png
,D/NtpTrustedTime(  887): currentTimeMillis() cache hit
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
,D/FileShare-Server( 8516): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,V/BluetoothEventManager( 1306): Received android.bluetooth.adapter.action.STATE_CHANGED
D/WifiCredService( 1306): Action received :android.net.wifi.WIFI_STATE_CHANGED
,I/ActivityManager(  887): Killing 6635:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,I/Hs20UtilService( 1306): Starting #13
I/Hs20UtilService( 1306): Message received 5007
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7485): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7485): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7485): StateMachine : Current State = 1
,D/SecurityLogAgent( 7485): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 1754): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
,D/com.peel.receiver.ConnectivityActionReceiver( 1754): NO active network... no services...
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): last run: 1449670518662 -- System.currentTimeMillis()-last_run: 11000557
D/com.peel.receiver.ConnectivityActionReceiver( 1754): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): ... skip last_72_check
,I/ActivityManager(  887): Process com.android.bluetooth (pid 3246)(adj 0) has died(56,553)
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 1306): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1306): onReceive
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8547): MountEmulatedStorage()
,E/Zygote  ( 8547): v2
I/libpersona( 8547): KNOX_SDCARD checking this for 1002
I/libpersona( 8547): KNOX_SDCARD not a persona
,I/ActivityManager(  887): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=8547 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/SELinux ( 8547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8547): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  887): failed to open /acct/uid_10012/pid_6635/cgroup.procs: No such file or directory
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 8547): TimaSignature is unavailable
,I/ApplicationPolicy(  887): updateDataUsageMap
,D/ActivityThread( 8547): Added TimaKeyStore provider
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2102): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  887): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5343): type=WIFI subType= reason=null isConnected=false
,I/SystemBroadcastReceiver( 7081): [#DCM#] [DCM_Performance] onReceive completed in time  937 microsec. 
,I/DBG_DM  ( 3856): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7081): [#DCM#] Calling notifyListeners. 
I/DBG_DM  ( 3856): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
I/DCMController( 7081): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
D/Tethering(  887): MasterInitialState.processMessage what=3
I/DCMController( 7081): [#DCM#] setIsConnectedForExtractors 
D/SmartBondingService(  887): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  887): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  887): CLoinfo wifi false
,D/SmartBondingService(  887): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  887): getSBEnabled() enabled =false
D/SmartBondingService(  887): getSBEnabled() enabled =false
D/SmartBondingService(  887): getSBEnabled() enabled =false
,W/SLocation(  887): No Active Data Connection
,D/SmartBondingService(  887): getNetworkEnabled : wifi : false mobile : true
,D/ResourcesManager( 8547): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager( 8547): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 8547): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 8547): Load D/L JNI Library
,I/BluetoothA2dpSinkServiceJni( 8547): register_com_android_bluetooth_a2dp_sink
,D/BluetoothAdapterApp( 8547): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1f164d33 Instance Count = 1
,D/BluetoothAdapterApp( 8547): onCreate
,D/BtSettings.ProfileConfig( 8547): Adding GattService
,D/BtSettings.ProfileConfig( 8547): Adding HeadsetService
,D/BtSettings.ProfileConfig( 8547): Adding A2dpService
,D/BtSettings.ProfileConfig( 8547): Adding HidService
,D/BtSettings.ProfileConfig( 8547): Adding HealthService
,D/BtSettings.ProfileConfig( 8547): Adding PanService
D/BtSettings.ProfileConfig( 8547): Adding BluetoothMapService
,D/BtSettings.ProfileConfig( 8547): Adding SapService
,D/BtSettings.ProfileConfig( 8547): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 8547): Adding A2dpSinkService
,D/BtSettings.ProfileConfig( 8547): Adding SapClientService
,D/BtSettings.ProfileConfig( 8547): Adding HidDevService
I/BtSettings.ProfileConfig( 8547): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider(  887): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider(  887): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  887): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  887): selectionArgs: false
D/SettingsProvider(  887): selectionArgs: 1002
D/SecContentProvider(  887): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  887): ret = -1
,D/SettingsProvider(  887): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider(  887): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  887): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  887): selectionArgs: false
D/SettingsProvider(  887): selectionArgs: 1002
D/SecContentProvider(  887): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  887): ret = -1
,D/SettingsProvider(  887): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider(  887): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  887): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  887): selectionArgs: false
D/SettingsProvider(  887): selectionArgs: 1002
D/SecContentProvider(  887): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  887): ret = -1
,D/SettingsProvider(  887): name = bt_svcst_com.android.bluetooth.hid.HidService,
D/SettingsProvider(  887): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  887): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  887): selectionArgs: false
D/SettingsProvider(  887): selectionArgs: 1002
D/SecContentProvider(  887): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  887): ret = -1
,D/SettingsProvider(  887): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider(  887): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  887): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  887): selectionArgs: false
D/SettingsProvider(  887): selectionArgs: 1002
D/SecContentProvider(  887): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  887): ret = -1
D/SettingsProvider(  887): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider(  887): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  887): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  887): selectionArgs: false
D/SettingsProvider(  887): selectionArgs: 1002
D/SecContentProvider(  887): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  887): ret = -1
D/SettingsProvider(  887): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider(  887): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  887): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  887): selectionArgs: false
D/SettingsProvider(  887): selectionArgs: 1002
D/SecContentProvider(  887): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  887): ret = -1
D/SettingsProvider(  887): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider(  887): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  887): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  887): selectionArgs: false
D/SettingsProvider(  887): selectionArgs: 1002
D/SecContentProvider(  887): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  887): ret = -1
D/SettingsProvider(  887): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider(  887): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  887): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  887): selectionArgs: false
D/SettingsProvider(  887): selectionArgs: 1002
D/SecContentProvider(  887): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  887): ret = -1
D/SettingsProvider(  887): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider(  887): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  887): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  887): selectionArgs: false
D/SettingsProvider(  887): selectionArgs: 1002
D/SecContentProvider(  887): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  887): ret = -1
D/SettingsProvider(  887): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider(  887): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  887): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  887): selectionArgs: false
D/SettingsProvider(  887): selectionArgs: 1002
D/SecContentProvider(  887): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  887): ret = -1
D/SettingsProvider(  887): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider(  887): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  887): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  887): selectionArgs: false
D/SettingsProvider(  887): selectionArgs: 1002
D/SecContentProvider(  887): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  887): ret = -1
D/BluetoothAdapterApp( 8547): checkSWUpdate
D/BluetoothAdapterApp( 8547): sw version in prop is 1428568983
,D/BluetoothAdapterApp( 8547): sw version in file is 1428568983
D/BluetoothAdapterApp( 8547): sw version is same
,I/ActivityManager(  887): Killing 7036:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,D/AuthorizationBluetoothService( 1673): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7485): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7485): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 7485): StateMachine : Current State = 1
D/SecurityLogAgent( 7485): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 1754): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
,D/com.peel.receiver.ConnectivityActionReceiver( 1754): NO active network... no services...
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): last run: 1449670518662 -- System.currentTimeMillis()-last_run: 11000992
D/com.peel.receiver.ConnectivityActionReceiver( 1754): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): ... skip last_72_check
,I/PCWCLIENTTRACE_PushUtil( 7535): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7535): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7535): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7535): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 7535): noConnectivity : true
,I/DIAGMON_AGENT( 7573): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7573): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,W/libprocessgroup(  887): failed to open /acct/uid_10170/pid_7036/cgroup.procs: No such file or directory
,I/FOTA_Client( 7592): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7592): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7592): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7592): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7592): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7612): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7612): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449681520025
,I/KLMS-2.4.503: ( 7612): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7612): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7612): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7627): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7672): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 7712): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7712): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 7712): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7712): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7712): [OR] == isSIMCardReady false ==
,I/SA      ( 7712): [SCU] == networkStateCheck == false
I/SA      ( 7712): [OR] onReceive END
,E/SPPClientService( 7672): [[SystemStateMonitorService]] No Active Internet
,D/accuweather( 7260): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7260): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7752): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7752): premStatus:2
,I/KnoxUsageLogPro( 7752): isEulaShown : false
I/KnoxUsageLogPro( 7752): KnoxUsageReceiver onReceive : not Processible, just return
,D/Headlines( 5492): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5492): getCountryCode(): countryCode = DE
,D/Headlines( 5492): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5492): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5492): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5492): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5492): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5492): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5492): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect( 7868): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7868): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7868): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService(  887): exchangeData() failure , invalid userId
,D/RCPManagerService(  887): exchangeData() failure , invalid userId
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7485): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7485): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7485): StateMachine : Current State = 1
D/SecurityLogAgent( 7485): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 1754): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
,D/com.peel.receiver.ConnectivityActionReceiver( 1754): NO active network... no services...
,D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): 
D/com.peel.receiver.ConnectivityActionReceiver( 1754): last run: 1449670518662 -- System.currentTimeMillis()-last_run: 11001938
D/com.peel.receiver.ConnectivityActionReceiver( 1754): ... skip 
,D/com.peel.receiver.ConnectivityActionReceiver( 1754): ... skip last_72_check
,I/iu.Environment( 2442): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2442): num queued entries: 0
,I/iu.UploadsManager( 2442): num updated entries: 0
,I/iu.SyncManager( 2442): NEXT; no task
,D/ChimeraCfgMgr( 2442): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/PowerManagerService(  887): [PWL] Off : 330s ago
,I/PowerManagerService(  887): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  887): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  887): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=887, ws=null) (elapsedTime=2814)
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  887): waitForAlarm result :4
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0,
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/bootchecker(  320): bootchecker wake up!!
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :8
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 16
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  887): Failed to find a new network - expiring NetTransition Wakelock
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 17
,I/PowerManagerService(  887): [PWL] Off : 390s ago
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 18
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Daemon(  324): Stop the daemon....
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 19
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  887): [PWL] Off : 455s ago
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  285): DCD ON
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  887): stay LED for fully charged
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/TimaService(  887): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  887): TimaServiceHandler.handleMessage what =1
,D/TimaService(  887): TIMA: checkEvent, operation: 50000 subject: 10000
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  887): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  887): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  887): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  887): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/ActivityManager(  887): Killing 6135:com.google.android.gm/u0a114 (adj 15): bgCount ##41
,W/libprocessgroup(  887): failed to open /acct/uid_10114/pid_6135/cgroup.procs: No such file or directory
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 21
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,I/PowerManagerService(  887): [PWL] Off : 525s ago
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 22
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 23
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  887): !@Sync 24
,I/PowerManagerService(  887): [PWL] Off : 600s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged,
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 25
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 26
,V/AlarmManager(  887): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/Finsky  ( 6592): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/LightsService(  887): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  887): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  887): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/art     ( 1673): Explicit concurrent mark sweep GC freed 40468(2MB) AllocSpace objects, 31(2MB) LOS objects, 40% free, 18MB/30MB, paused 2.943ms total 105.004ms
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 2442): Aggregate from 1449679503627 (log), 1449679503627 (data)
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6592): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  887): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  887): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  887): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  887): unregisterListener ::   
,D/LightsService(  887): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  887): Explicit concurrent mark sweep GC freed 82055(6MB) AllocSpace objects, 145(2MB) LOS objects, 30% free, 36MB/52MB, paused 2.839ms total 231.912ms
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6592): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/SMD     (  285): DCD ON
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6592): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6592): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6592): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6592): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,D/DeviceConnectionService( 2186): client connected with version: 7571000
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  887): waitForAlarm result :4
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  887): stay LED for fully charged
D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6592): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6592): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6592): [1] 5.onFinished: Scheduling replication attempt 1.
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  887): [PWL] Off : 680s ago
,E/SMD     (  285): DCD ON,
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 27
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :4
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6592): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6592): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6592): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): stay LED for fully charged
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6592): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6592): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6592): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 28
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :4
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6592): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6592): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6592): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 29
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :4
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6592): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6592): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6592): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,I/PowerManagerService(  887): [PWL] Off : 765s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  887): waitForAlarm result :8
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/TimaService(  887): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  887): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  887): TimaServiceHandler.handleMessage what =1
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 30
,V/AlarmManager(  887): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,I/TLC_TIMA_PKM_measure_kernel(  887): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  887): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/TimaService(  887): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  887): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  887): stay LED for fully charged
D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6592): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6592): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6592): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 31
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  887): waitForAlarm result :4
,I/DBG_DM  ( 3856): [com.wssyncmldm.lllIlIlIIIllIIlIllIl(350/onReceive)] FotaPostpone callback received
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/BatteryService(  887): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/DBG_DM  ( 3856): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 3
,D/LightsService(  887): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 887) 
,D/LightsService(  887): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x42 -> 0x42 | SvcLED(id=4) set On
,E/LightSensor(  887): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  887): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,I/DBG_DM  ( 3856): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 0
,I/DBG_DM  ( 3856): [IIllIlIIlIlllIIllIII(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 3856): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,I/DBG_DM  ( 3856): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3856): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,I/DBG_DM  ( 3856): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,I/DBG_DM  ( 3856): [IIllIlIIlIlllIIllIII(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 3856): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,I/DBG_DM  ( 3856): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
,E/DBG_DM  ( 3856): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,E/DBG_DM  ( 3856): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@17142747
,I/DBG_DM  ( 3856): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3856): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
,D/SecContentProvider2(  887): mCursor = null
D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  887): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy(  887): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager(  887): showStatusBarByNotification() mOpenByNotification=false
,V/BitmapFactory( 1172): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_completion.qmg
,V/BitmapFactory( 1172): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_completion.qmg
,D/KnoxNotification( 1172): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 1172): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1172): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1172): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@2e4b6dcb
,D/SecContentProvider2(  887): uri = 14 selection = getSealedState
D/SecContentProvider2(  887): mCursor = null
D/SecContentProvider2(  887): KnoxCustomManagerService offline: service is not available
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,I/DBG_DM  ( 3856): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,D/OpenGLRenderer( 3856): Render dirty regions requested: true
,I/DBG_DM  ( 3856): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/SurfaceFlinger(  249): id=18 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/DBG_DM  ( 3856): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3856): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/DBG_DM  ( 3856): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
D/PowerManagerService(  887): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=887
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/Adreno-EGL( 3856): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3856): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 3856): Build Date: 03/03/15 Tue
I/Adreno-EGL( 3856): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 3856): Remote Branch: 
I/Adreno-EGL( 3856): Local Patches: 
I/Adreno-EGL( 3856): Reconstruct Branch: 
,I/OpenGLRenderer( 3856): Initialized EGL, version 1.4
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/OpenGLRenderer( 3856): HWUI protection enabled for context ,  &this =0xaf822088 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 3856): Enabling debug mode 0
,E/LightSensor(  887): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  887): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  887): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  887): unregisterListener ::   
D/LightsService(  887): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
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
,E/SMD     (  285): DCD ON
,I/SurfaceFlinger(  249): id=18 Removed Toast (8/9)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/PowerManagerService(  887): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 887) eventTime = 964224
,D/PowerManagerService(  887): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=887 (0x0)
,D/PowerManagerService(  887): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=887, ws=WorkSource{1000}) (elapsedTime=3518)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,V/AlarmManager(  887): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 32
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  887): stay LED for fully charged
D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  887): stay LED for fully charged
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  887): [PWL] Off : 855s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,D/BatteryService(  887): stay LED for fully charged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 33
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 280, PST = 288, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 280, PST = 287, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 34
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 280, PST = 286, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 284, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 282, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 35
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 280, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 278, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  887): [PWL] Off : 950s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 276, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 36
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 274, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 273, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 272, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 37
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 271, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,D/BatteryService(  887): stay LED for fully charged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 38
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 39
,I/PowerManagerService(  887): [PWL] Off : 1050s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/TimaService(  887): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  887): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  887): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,I/UsageStatsService(  887): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  887): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  887): Updating Usage Statistics in DB @ 1449682267212
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
,W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  887): ::getAppControlDB: Exception to create DB
W/System.err(  887): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  887): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  887): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  887): Done Updating Usage Statistics in DB @ 1449682267433
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel(  887): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  887): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  887): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  887): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 290, PST = 272, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,D/BatteryService(  887): stay LED for fully charged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 41
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 272, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/BatteryService(  887): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 42
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  887): [PWL] Off : 1155s ago
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 272, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 43
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 44
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 45
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 46
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  887): [PWL] Off : 1265s ago
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,D/BatteryService(  887): stay LED for fully charged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 47
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 48
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 49
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/TimaService(  887): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  887): TimaServiceHandler.handleMessage what =1
,D/TimaService(  887): TIMA: checkEvent, operation: 50000 subject: 10000
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel(  887): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  887): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  887): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  887): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,D/BatteryService(  887): stay LED for fully charged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  887): [PWL] Off : 1380s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 51
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 52
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 53
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,D/BatteryService(  887): stay LED for fully charged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 54
,I/PowerManagerService(  887): [PWL] Off : 1500s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 55
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 56
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 57
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 58
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  887): [PWL] Off : 1625s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  887): stay LED for fully charged
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 59
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,E/SMD     (  285): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/NetworkStatsFactory(  887): UpdateStatsForKnox
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
I/MotionRecognitionService(  887): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/BatteryService(  887): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/TimaService(  887): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  887): TimaServiceHandler.handleMessage what =1
,D/TimaService(  887): TIMA: checkEvent, operation: 50000 subject: 10000
,E/Watchdog(  887): !@Sync 60
,E/SMD     (  285): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  887): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  887): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  887): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  887): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,V/AlarmManager(  887): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,I/ProcessStatsService(  887): Prepared write state in 17ms
,D/LightsService(  887): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  887): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  887): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,I/ProcessStatsService(  887): Prepared write state in 32ms
,V/NetworkStats(  887): performPollLocked(flags=0x3)
,D/NtpTrustedTime(  887): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  887): UpdateStatsForKnox
,D/ConnectivityService(  887): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  887): performPollLocked() took 15ms
,D/NtpTrustedTime(  887): currentTimeMillis() cache hit
,D/NtpTrustedTime(  887): currentTimeMillis() cache hit
D/NtpTrustedTime(  887): currentTimeMillis() cache hit
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GLSUser ( 1673): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1673): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1673): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1673): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1673): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  887): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  887): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  887): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  887): unregisterListener ::   
,D/LightsService(  887): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,E/SQLiteLog( 1673): (10) POSIX Error : 11 SQLite Error : 3850
,I/ProcessStatsService(  887): Pruning old procstats: /data/system/procstats/state-2015-12-09-03-33-25.bin
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 61
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,V/AlarmManager(  887): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 62
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  887): [PWL] Off : 1755s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  887): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  887): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  887): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  887):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  887): Plugged
,I/MotionRecognitionService(  887): setPowerConnected  = true
,D/BatteryService(  887): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  887): !@Sync 63
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  887): SIOP:: AP = 270, PST = 270, CUR = 300
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8792): 
D/AndroidRuntime( 8792): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8792): CheckJNI is OFF
D/AndroidRuntime( 8792): setted country_code = Germany
D/AndroidRuntime( 8792): setted countryiso_code = DE
D/AndroidRuntime( 8792): setted sales_code = DBT
D/AndroidRuntime( 8792): readGMSProperty: start
D/AndroidRuntime( 8792): readGMSProperty: already setted!!
D/AndroidRuntime( 8792): readGMSProperty: end
D/AndroidRuntime( 8792): addProductProperty: start
E/AffinityControl( 8792): AffinityControl: registerfunction enter
D/AndroidRuntime( 8792): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  887): START PACKAGE DELETE: observer{823469389}
D/PackageManager(  887): pkg{<packageName>}
D/PackageManager(  887): user{0}
D/PackageManager(  887): caller{2000}
D/PackageManager(  887): flags{3}
D/PersonaManagerService(  887): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  887): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  887): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  887): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  887): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  887): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  887): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  887): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  887): getApplicationUninstallationEnabled
D/ApplicationPolicy(  887): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  887): !@killApplicatoin: 10367, uninstall pkg
I/ActivityManager(  887): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
I/ActivityManager(  887): Killing 7421:com.test.thalitest/u0a367 (adj 0): stop com.test.thalitest
I/ActivityManager(  887): Killing 7908:com.sec.android.provider.badge/u0a78 (adj 15): empty for 1804s
I/ActivityManager(  887): Killing 7081:com.samsung.dcm:DCMService/u0a4 (adj 15): empty for 1805s
I/ActivityManager(  887): Killing 7174:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): empty for 1811s
I/ActivityManager(  887): Killing 7322:com.sec.android.app.camera/u0a154 (adj 15): empty for 1826s
I/ActivityManager(  887): Killing 7304:com.sec.android.GeoLookout/u0a113 (adj 15): empty for 1826s
I/ActivityManager(  887): Killing 7284:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): empty for 1826s
I/ActivityManager(  887): Killing 7254:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): empty for 1826s
I/ActivityManager(  887): Killing 5639:com.android.mms/u0a50 (adj 15): empty for 1827s
I/ActivityManager(  887): Killing 5968:com.sec.android.gallery3d/u0a48 (adj 15): empty for 1827s
I/ActivityManager(  887): Killing 4928:com.android.defcontainer/u0a5 (adj 15): empty for 1838s
I/ActivityManager(  887): Killing 4724:com.google.android.gms.wearable/u0a12 (adj 15): empty for 1839s
I/ActivityManager(  887): Killing 7121:com.sec.android.app.music:service/u0a44 (adj 15): empty for 1845s
I/ActivityManager(  887):   Force finishing activity ActivityRecord{29b5f68b u0 com.test.thalitest/.MainActivity t11}
D/FocusedStackFrame(  887): Set to : 0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ConnectivityService(  887): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiService(  887): Client connection lost with reason: 4
W/PackageSettings(  887): Skipping PackageSetting{39d61a98 com.example.hello/10374} due to missing metadata
D/CountryDetector(  887): No listener is left
I/ActivityManager(  887): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
I/art     ( 4668): Explicit concurrent mark sweep GC freed 4116(230KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 375us total 23.008ms
I/art     ( 1571): Explicit concurrent mark sweep GC freed 10522(704KB) AllocSpace objects, 1(39KB) LOS objects, 39% free, 16MB/27MB, paused 432us total 20.529ms
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/ResourcesManager( 1471): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
W/ResourcesManager( 1471): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/InputReader(  887): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1862): mOCRHelper is null
D/ResourcesManager( 1471): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
W/ResourcesManager( 1471): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
W/GeofencerStateMachine( 2186): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.4.503: ( 7612): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.503: ( 7612): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449682962109
I/KLMS-2.4.503: ( 7612): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.503: ( 7612): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
I/art     (  887): Explicit concurrent mark sweep GC freed 86971(9MB) AllocSpace objects, 346(5MB) LOS objects, 30% free, 37MB/53MB, paused 1.455ms total 197.932ms
D/ResourcesManager(  887): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  887): WaitForGcToComplete blocked for 180.211ms for cause Explicit
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/RegisteredServicesCache( 1459): empty dynamic service
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
E/SMD     (  285): DCD ON
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
I/art     (  887): Explicit concurrent mark sweep GC freed 15302(755KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 2.151ms total 178.055ms
I/art     (  887): WaitForGcToComplete blocked for 166.990ms for cause Explicit
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/art     (  887): Explicit concurrent mark sweep GC freed 3991(165KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 1.426ms total 80.575ms
D/SecContentProvider2(  887): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  887): mCursor = null
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
E/Zygote  ( 8821): MountEmulatedStorage()
E/Zygote  ( 8821): v2
I/libpersona( 8821): KNOX_SDCARD checking this for 10104
I/libpersona( 8821): KNOX_SDCARD not a persona
D/ResourcesManager(  887): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/ActivityManager(  887): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8821 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
D/PackageManager(  887): delete codoeFile: 
I/SELinux ( 8821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8821): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PackageManager(  887): result of delete: 1{823469389}
D/RCPManagerService(  887): PackageReceiver onReceive()
I/HarmonyEASService(  887): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  887): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  887): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/JobSchedulerService(  887): Receieved: android.intent.action.PACKAGE_REMOVED
W/libprocessgroup(  887): failed to open /acct/uid_10154/pid_7322/cgroup.procs: No such file or directory
D/AndroidRuntime( 8792): Shutting down VM
V/EnterpriseBillingPolicy(  887): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  887): uID is 10367
V/EnterpriseBillingPolicy(  887): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  887): getProfileForApplication - enter
W/libprocessgroup(  887): failed to open /acct/uid_10012/pid_4724/cgroup.procs: No such file or directory
V/EnterpriseBillingPolicyStorage(  887): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  887): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  887): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  887): getBillingProfileForVpnEngine - start - com.test.thalitest
W/libprocessgroup(  887): failed to open /acct/uid_10103/pid_7284/cgroup.procs: No such file or directory
V/EnterpriseBillingPolicyStorage(  887): getBillingProfileForVpnEngine - end - null
W/libprocessgroup(  887): failed to open /acct/uid_10094/pid_7254/cgroup.procs: No such file or directory
W/libprocessgroup(  887): failed to open /acct/uid_10048/pid_5968/cgroup.procs: No such file or directory
W/libprocessgroup(  887): failed to open /acct/uid_10005/pid_4928/cgroup.procs: No such file or directory
D/TaskPersister(  887): removeObsoleteFile: deleting file=11_task.xml
D/TaskPersister(  887): removeObsoleteFile: deleting file=11_task_thumbnail.png
W/libprocessgroup(  887): failed to open /acct/uid_10044/pid_7121/cgroup.procs: No such file or directory
W/libprocessgroup(  887): failed to open /acct/uid_10004/pid_7081/cgroup.procs: No such file or directory
W/libprocessgroup(  887): failed to open /acct/uid_10113/pid_7304/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 8821): TimaSignature is unavailable
W/libprocessgroup(  887): failed to open /acct/uid_10158/pid_7174/cgroup.procs: No such file or directory
W/libprocessgroup(  887): failed to open /acct/uid_10078/pid_7908/cgroup.procs: No such file or directory
D/ActivityThread( 8821): Added TimaKeyStore provider
W/libprocessgroup(  887): failed to open /acct/uid_10050/pid_5639/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ResourcesManager( 8821): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/SurfaceWidgetView( 1471): destroyHardwareResources():140859509
V/WindowOrientationListener(  887): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  887): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  887): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  887): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  887): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/Launcher( 1471): onRestart, Launcher: 649752518
D/Launcher( 1471): onStart, Launcher: 649752518
D/Launcher.HomeView( 1471): onStart
D/elm:14451( 8821): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8821): ELMEngine.ELMEngine( context ).
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2102): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2102): [237392/6] SurfaceWidget drawing first frame
D/elm:14451( 8821): MDMBridge.setEnterpriseBridge()
D/elm:14451( 8821): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/elm:14451( 8821): ElmAgentService : onCreate()
D/elm:14451( 8821): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8821): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8821): MDMBridge.getInstance()
D/elm:14451( 8821): MDMBridge.getAllLicenseInfoFromSDK()
I/SurfaceFlinger(  249): id=19 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
E/Zygote  ( 8839): MountEmulatedStorage()
I/libpersona( 8839): KNOX_SDCARD checking this for 10017
E/Zygote  ( 8839): v2
I/libpersona( 8839): KNOX_SDCARD not a persona
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/StatusBarManagerService(  887): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1172): value : false
D/elm:14451( 8821): MDMBridge.getAllLicenseInfoFromSDK()
I/ActivityManager(  887): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8839 uid=10017 gids={50017, 9997} abi=armeabi-v7a
I/SELinux ( 8839): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/SELinux ( 8839): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8839): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/StatusBarManagerService(  887): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/elm:14451( 8821): ElmAgentService : onDestroy().
D/TimaKeyStoreProvider( 8839): TimaSignature is unavailable
D/ActivityThread( 8839): Added TimaKeyStore provider
W/ContextImpl(  887): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/InputMethodManagerService(  887): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  887): Got RemoteException sending setActive(false) notification to pid 7421 uid 10367
D/EnterpriseDeviceManagerService(  887): Package has changed for user 0
D/EnterpriseDeviceManagerService(  887): Admin package name: com.google.android.gms
D/ResourcesManager( 8839): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8839): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8839): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8839): onReceive() : package name is not s health. Return !!!
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
I/PCWCLIENTTRACE_PushUtil( 7535): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7535): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7535): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7535): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
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
E/Zygote  ( 8858): MountEmulatedStorage()
E/Zygote  ( 8858): v2
I/libpersona( 8858): KNOX_SDCARD checking this for 10034
I/libpersona( 8858): KNOX_SDCARD not a persona
I/ActivityManager(  887): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8858 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
I/SELinux ( 8858): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/SELinux ( 8858): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8858): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/Timeline(  887): Timeline: Activity_windows_visible id: ActivityRecord{3ce641c4 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:1907475
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
D/TimaKeyStoreProvider( 8858): TimaSignature is unavailable
D/ActivityThread( 8858): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ResourcesManager( 8858): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(  887): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  887): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  887): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/FeatureConfig( 8858): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
D/ResourcesManager(  887): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
D/ResourcesManager(  887): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  887): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  887): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  887): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager(  887): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  887): onPackageRemoved : com.test.thalitest
D/ResourcesManager( 8858): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager( 8858): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8858): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8858): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8858): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8858): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 8858): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager( 8858): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 8858): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8858): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8858): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8858): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8858): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8858): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ResourcesManager( 8858): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 8858): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager( 8858): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ResourcesManager( 8858): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 8858): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8858): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8858): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 8858): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/ResourcesManager( 8858): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8858): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8858): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.

```
