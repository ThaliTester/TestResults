#### Test 549702613245198_thali07_samsung-SM-G900F Logs


```
--------- beginning of main,
E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
--------- beginning of system
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7502): Authentication error
E/BooksAccountManager( 7502): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7502): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7502): null auth token
I/qtaguid ( 7502): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7502, getuid(): 10082
I/qtaguid ( 7502): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7502, getuid(): 10082
I/qtaguid ( 7502): Untagging socket 34
W/ApiaryClient( 7502): Error response from books API: {
W/ApiaryClient( 7502):  "error": {
W/ApiaryClient( 7502):   "errors": [
W/ApiaryClient( 7502):    {
W/ApiaryClient( 7502):     "domain": "global",
W/ApiaryClient( 7502):     "reason": "required",
W/ApiaryClient( 7502):     "message": "Login Required",
W/ApiaryClient( 7502):     "locationType": "header",
W/ApiaryClient( 7502):     "location": "Authorization"
W/ApiaryClient( 7502):    }
W/ApiaryClient( 7502):   ],
W/ApiaryClient( 7502):   "code": 401,
W/ApiaryClient( 7502):   "message": "Login Required"
W/ApiaryClient( 7502):  }
W/ApiaryClient( 7502): }
W/ApiaryClient( 7502): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7502): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4866812771580682236&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7502): Headers suppressed
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
D/AndroidRuntime( 7564): 
D/AndroidRuntime( 7564): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7564): CheckJNI is OFF
D/AndroidRuntime( 7564): setted country_code = Germany
D/AndroidRuntime( 7564): setted countryiso_code = DE
D/AndroidRuntime( 7564): setted sales_code = DBT
D/AndroidRuntime( 7564): readGMSProperty: start
D/AndroidRuntime( 7564): readGMSProperty: already setted!!
D/AndroidRuntime( 7564): readGMSProperty: end
D/AndroidRuntime( 7564): addProductProperty: start
E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
E/SMD     (  282): DCD ON
E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
E/AffinityControl( 7564): AffinityControl: registerfunction enter
E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
D/AndroidRuntime( 7564): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  874): inState():  stateMachine is null !!
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  874): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  874): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  874): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 874  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  874): mDVFSHelper.acquire()
D/FocusedStackFrame(  874): Set to : 0
D/Launcher.HomeView( 1462): onPause
D/Launcher( 1462): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 7564): Shutting down VM
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
V/TaskCloserActivity( 7335): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
E/Zygote  ( 7586): MountEmulatedStorage()
I/libpersona( 7586): KNOX_SDCARD checking this for 10367
E/Zygote  ( 7586): v2
I/libpersona( 7586): KNOX_SDCARD not a persona
I/ActivityManager(  874): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7586 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7586): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/SELinux ( 7586): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7586): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/StatusBarManagerService(  874): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
I/MicrophoneInputStream( 1556): mic_close gfk@f3bd30
D/LockPatternUtilsCache( 1173): value : false
D/TimaKeyStoreProvider( 7586): TimaSignature is unavailable
D/ActivityThread( 7586): Added TimaKeyStore provider
V/WindowOrientationListener(  874): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  874): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  874): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  874): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  874): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/AudioPolicyManager(  290): stopInput() input 30
D/Launcher.HomeView( 1462): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2188): [237392/6] Surface widget pause on instance = 1
V/audio_hw_primary(  290): in_standby: enter
D/accuweather( 2188): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2188): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2188): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2188): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/HotwordRecognitionRnr( 1556): Hotword detection finished
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/HotwordRecognitionRnr( 1556): Stopping hotword detection.
V/ActivityManager(  874): Display changed displayId=0
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2188): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2188): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/SurfaceWidgetView( 1462): destroyHardwareResources():437003284
E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/ResourcesManager( 7586): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
V/audio_hw_primary(  290): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  290): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  290): disable_audio_route: reset mixer path: audio-record
D/audio_route(  290): ++++ audio_route_update_mixer ==============
D/audio_route(  290): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  290): Setting mixer control: value: 0
D/audio_route(  290): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  290): disable_audio_route: exit
V/audio_hw_primary(  290): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  290): ++++ audio_route_update_mixer ==============
D/audio_route(  290): Setting mixer control: DEC2 Volume
D/audio_route(  290): Setting mixer control: value: 0
D/audio_route(  290): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  290): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  290): Setting mixer control: value: 0
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/audio_route(  290): Setting mixer control: DEC2 MUX, value: 0
D/StatusBarManagerService(  874): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/audio_route(  290): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  290): stop_input_stream: exit: status(0)
V/audio_hw_primary(  290): in_standby: exit:  status(0)
V/AudioPolicyManager(  290): releaseInput() 30
V/AudioPolicyManager(  290): closeInput(30)
V/audio_hw_primary(  290): adev_close_input_stream
V/audio_hw_primary(  290): in_standby: enter
V/audio_hw_primary(  290): in_standby: exit:  status(0)
E/audio_hw_primary(  290): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  290): releaseInput() exit
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/Launcher( 1462): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/SurfaceWidgetView( 1462): destroyHardwareResources():437003284
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/WebViewFactory( 7586): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7586): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  874): CMD_RSSI_POLL : out!
I/LibraryLoader( 7586): Loading: webviewchromium
I/LibraryLoader( 7586): Time to load native libraries: 3 ms (timestamps 5156-5159)
I/LibraryLoader( 7586): Expected native library version number "",actual native library version number ""
E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
V/WebViewChromiumFactoryProvider( 7586): Binding Chromium to main looper Looper (main, tid 1) {256ecb11}
I/LibraryLoader( 7586): Expected native library version number "",actual native library version number ""
I/chromium( 7586): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/BrowserStartupController( 7586): Initializing chromium process, renderers=0
W/art     ( 7586): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
W/chromium( 7586): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7586): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7586): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/Adreno-EGL( 7586): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7586): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7586): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7586): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7586): Remote Branch: 
I/Adreno-EGL( 7586): Local Patches: 
I/Adreno-EGL( 7586): Reconstruct Branch: 
I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
E/BooksAccountManager( 7502): Authentication error
E/BooksAccountManager( 7502): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7502): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7502): null auth token
I/qtaguid ( 7502): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7502, getuid(): 10082
D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
W/chromium( 7586): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
W/chromium( 7586): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/art     ( 7586): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7586): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/SystemWebViewEngine( 7586): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/qtaguid ( 7502): Untagging socket 34
W/ApiaryClient( 7502): Error response from books API: {
W/ApiaryClient( 7502):  "error": {
W/ApiaryClient( 7502):   "errors": [
W/ApiaryClient( 7502):    {
W/ApiaryClient( 7502):     "domain": "global",
W/ApiaryClient( 7502):     "reason": "required",
W/ApiaryClient( 7502):     "message": "Login Required",
W/ApiaryClient( 7502):     "locationType": "header",
W/ApiaryClient( 7502):     "location": "Authorization"
W/ApiaryClient( 7502):    }
W/ApiaryClient( 7502):   ],
W/ApiaryClient( 7502):   "code": 401,
W/ApiaryClient( 7502):   "message": "Login Required"
W/ApiaryClient( 7502):  }
W/ApiaryClient( 7502): }
W/ApiaryClient( 7502): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7502): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4866812771580682236&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7502): Headers suppressed
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/art     ( 7586): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7586): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/Activity( 7586): performCreate Call secproduct feature valuefalse
D/Activity( 7586): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/OpenGLRenderer( 7586): Render dirty regions requested: true
D/ActivityManager(  874): post active user change for 0
D/KnoxTimeoutHandler(  874): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  874): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/OpenGLRenderer( 7586): Initialized EGL, version 1.4
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/OpenGLRenderer( 7586): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7586): Enabling debug mode 0
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/InputMethodManagerService(  874): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager(  874): Displayed com.test.thalitest/.MainActivity: +634ms
E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/Timeline( 7586): Timeline: Activity_idle id: android.os.BinderProxy@3b850668 time:95535
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/JsMessageQueue( 7586): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/chromium( 7586): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7586): 
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (7/8)
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (-2/8)
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/CustomFrequencyManagerService(  874): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 874  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  874): mDVFSHelper.release()
I/Timeline(  874): Timeline: Activity_windows_visible id: ActivityRecord{259015d3 u0 com.test.thalitest/.MainActivity t11} time:95765
D/CustomFrequencyManagerService(  874): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 874  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
E/Adreno-ES20( 7586): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7586): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/jxcore_app_log( 7586): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359587200
,D/JX-Cordova( 7586): jxcore cordova android initializing
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  874): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 874  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/BooksSync( 7502): Soft error
E/BooksSync( 7502): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7502): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4866812771580682236&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7502): Headers suppressed
E/BooksSync( 7502): 
E/BooksSync( 7502): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7502): Sync error
E/BooksSync( 7502): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7502): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4866812771580682236&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7502): Headers suppressed
E/BooksSync( 7502): 
E/BooksSync( 7502): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7502): Finished books sync
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  874): Killing 6566:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,D/SyncManager(  874): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 63306, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  874): mCursor = null
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,W/libprocessgroup(  874): failed to open /acct/uid_10034/pid_6566/cgroup.procs: No such file or directory
,I/art     (  874): Explicit concurrent mark sweep GC freed 33303(1715KB) AllocSpace objects, 12(582KB) LOS objects, 30% free, 36MB/52MB, paused 1.518ms total 84.180ms
,D/PowerManagerService(  874): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1173 (0x0)
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/GAV2    ( 7502): Thread[GAThread,5,main]: No campaign data found.
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  874): SIOP:: AP = 360, PST = 418, CUR = 300
,W/jxcore-log( 7586): Initializing JXcore engine
,W/jxcore-log( 7586): JXcore engine is ready
,W/jxcore-log( 7586): Starting JXcore engine
,E/SMD     (  282): DCD ON
,E/auditd  ( 2131): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  874): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  874): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7648): MountEmulatedStorage()
E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
E/Zygote  ( 7648): v2
I/libpersona( 7648): KNOX_SDCARD checking this for 1000
I/libpersona( 7648): KNOX_SDCARD not a persona
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/ActivityManager(  874): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7648 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7648): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/jxcore-log( 7586): Platform android
W/jxcore-log( 7586): 
,W/jxcore-log( 7586): Process ARCH arm
W/jxcore-log( 7586): 
,D/TimaKeyStoreProvider( 7648): TimaSignature is unavailable
D/ActivityThread( 7648): Added TimaKeyStore provider
,D/ResourcesManager( 7648): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7648):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7648):  SeDenialReceiver : File path = null
,I/ActivityManager(  874): Killing 4606:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,W/libprocessgroup(  874): failed to open /acct/uid_10035/pid_4606/cgroup.procs: No such file or directory
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  874): CMD_RSSI_POLL : out!
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7586): JXcore Cordova bridge is ready!
I/jxcore-log( 7586): 
W/jxcore-log( 7586): JXcore engine is started
,I/Choreographer( 7586): Skipped 140 frames!  The application may be doing too much work on its main thread.
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7586): Toggling radios to true
I/jxcore-log( 7586): 
,D/BluetoothAdapter( 7586): enable()
,D/BluetoothAdapter( 7586): enable(): BT is already enabled..!
,D/WifiService(  874): New client listening to asynchronous messages
,I/WifiManager( 7586): packageName : com.test.thalitest
,D/SecContentProvider(  874): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  874): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  874): mCursor = null
,D/WifiService(  874): setWifiEnabled: true pid=7586, uid=10367
E/WifiService(  874): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  874): Permission Denial: getCurrentUser() from pid=7586, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  874): Failed getting userId using ActivityManagerNative
W/WifiService(  874): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7586, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  874): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  874): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  874): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  874): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  874): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  874): name = wifi_on
,I/WifiService(  874): disconnect: pid=7586, uid=10367
,I/wpa_supplicant( 1272): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7586): Radios toggled
I/jxcore-log( 7586): 
,I/wpa_supplicant( 1272): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1272): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1272): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1272): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  874): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1272): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1272): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1272): Disconnected - do not scan
I/wpa_supplicant( 1272): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  874): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  874): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  874): handleNetworkDisconnect "NG700" nid=0
,E/WifiConfigStore(  874): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  874): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  874): InactiveState{ what=143375 }
,D/WifiP2pService(  874): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/AlarmManager(  874): waitForAlarm result :4
,D/CommandListener(  275): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1638): Read error: ssl=0xaf927e00: I/O error during system call, Connection timed out
,E/WifiStateMachine(  874): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  874): updateNetworkInfo()
,D/ConnectivityService(  874): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  874): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,V/NativeCrypto( 1638): SSL shutdown failed: ssl=0xaf927e00: I/O error during system call, Broken pipe
,E/WifiConfigStore(  874): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  874): Start Disconnecting Watchdog 1
,I/WifiTrafficPoller(  874): evaluateTrafficStatsPolling
,D/ConnectivityService(  874): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,I/wpa_supplicant( 1272): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1272): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1272): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1272): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 1272): First Scan Start
,I/wpa_supplicant( 1272): Scan requested (ret=0) - scan timeout 30 seconds
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): ValidatedState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): DefaultState{ when=-6ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,I/CLocInfoService(  874): External Intent Received android.net.wifi.STATE_CHANGE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): Validated
,E/WifiStateMachine(  874): ConnectModeState: Network connection lost 
E/WifiStateMachine(  874): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg,
,E/WifiStateMachine(  874): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  874): InactiveState{ what=143375 }
D/WifiP2pService(  874): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  275): Clearing all IP addresses on wlan0
,D/ConnectivityService(  874): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  874): calling update connectivity
D/EntConnectivity(  874): Not allowed due to - mEnabled false
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,E/WifiStateMachine(  874): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/ConnectivityService(  874): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/WifiStateMachine(  874): updateConfiguredNetworkExpiration - currTime: 1452283671314
D/Nat464Xlat(  874): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/WifiStateMachine(  874): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524292
,D/ConnectivityService(  874): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  874): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/WifiTrafficPoller(  874): evaluateTrafficStatsPolling
,D/TelephonyNetworkFactory( 1455): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/Hs20UtilService( 1299): Starting #6
I/Hs20UtilService( 1299): Message received 5007
D/CSLegacyTypeTracker(  874): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,E/WifiStateMachine(  874): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  874): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  874): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,D/CSLegacyTypeTracker(  874): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService(  874): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  874): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  874): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  874): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  874): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  874): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  874): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  874): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  874): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  874): mCursor = null
,I/CLocInfoService(  874): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  874): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  874): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  874): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,V/NetworkStats(  874): updateIfacesLocked()
D/SmartBondingService(  874): getSBEnabled() enabled =false
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
V/NetworkStats(  874): performPollLocked(flags=0x1)
D/SmartBondingService(  874): getSBEnabled() enabled =false
D/SmartBondingService(  874): getSBEnabled() enabled =false
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1299): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1173): updateDataNetType()
,D/StatusBar.NetworkController( 1173): NoService, mRoamingIconId = 0
D/SmartBondingService(  874): getNetworkEnabled : wifi : true mobile : true
,D/NetworkStatsFactory(  874): UpdateStatsForKnox
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ConnectivityService(  874): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/ConnectivityService(  874): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/SecContentProvider2(  874): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  874): mCursor = null
,D/NtpTrustedTime(  874): currentTimeMillis() cache hit
,D/NtpTrustedTime(  874): currentTimeMillis() cache hit
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
V/NetworkStats(  874): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,V/NetworkStats(  874): performPollLocked() took 8ms
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1299): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1299): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1299): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 1173): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/NtpTrustedTime(  874): currentTimeMillis() cache hit
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
,I/Hs20UtilService( 1299): Starting #7
,I/Hs20UtilService( 1299): Message received 5007
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1299): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1299): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1299): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1299): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,V/AlarmManager(  874): waitForAlarm result :4
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6703): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6703): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6703): [1] 5.onFinished: Scheduling replication attempt 2.
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  874): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/SmartBondingService(  874): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  874): MasterInitialState.processMessage what=3
,D/SmartBondingService(  874): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  874): getSBEnabled() enabled =false
D/accuweather( 2188): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  874): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  874): CLoinfo wifi false
,D/SmartBondingService(  874): getSBEnabled() enabled =false
D/SmartBondingService(  874): getSBEnabled() enabled =false
,I/ApplicationPolicy(  874): updateDataUsageMap,
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,D/SmartBondingService(  874): getNetworkEnabled : wifi : true mobile : true
,I/SystemBroadcastReceiver( 7203): [#DCM#] [DCM_Performance] onReceive completed in time  8683 microsec. 
,I/SystemBroadcastReceiver( 7203): [#DCM#] Calling notifyListeners. 
I/DCMController( 7203): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7203): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/Zygote  ( 7718): MountEmulatedStorage()
I/libpersona( 7718): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7718): v2
I/libpersona( 7718): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7718 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/SLocation(  874): No Active Data Connection
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3811): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7718): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7718): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/NetworkMonitor( 5395): type=WIFI subType= reason=null isConnected=false
E/SELinux ( 7718): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3811): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7718): TimaSignature is unavailable
,D/ActivityThread( 7718): Added TimaKeyStore provider
,D/ResourcesManager( 7718): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 7718): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 7718): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7718): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 7718): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7718): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7718): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7718): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7718): noConnectivity : true
,V/AlarmManager(  874): waitForAlarm result :4
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7739): MountEmulatedStorage()
,E/Zygote  ( 7739): v2
I/libpersona( 7739): KNOX_SDCARD checking this for 10002
I/libpersona( 7739): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7739 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 6832:com.policydm/1000 (adj 15): bgCount ##41
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
I/SELinux ( 7739): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/SELinux ( 7739): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7739): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7739): TimaSignature is unavailable
,D/ActivityThread( 7739): Added TimaKeyStore provider
,D/ResourcesManager( 7739): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,W/libprocessgroup(  874): failed to open /acct/uid_1000/pid_6832/cgroup.procs: No such file or directory
,I/ActivityManager(  874): Killing 5125:com.sec.spp.push/u0a38 (adj 15): bgCount ##41
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7756): MountEmulatedStorage()
E/Zygote  ( 7756): v2
I/libpersona( 7756): KNOX_SDCARD checking this for 1000
I/libpersona( 7756): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7756 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7756): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7756): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7756): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7756): TimaSignature is unavailable
,D/ActivityThread( 7756): Added TimaKeyStore provider
,D/ResourcesManager( 7756): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
W/libprocessgroup(  874): failed to open /acct/uid_10038/pid_5125/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7756): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7756): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7756): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7756): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7756): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7756): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/wpa_supplicant( 1272): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 1272): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1272): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1272): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1272): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  874): [1,452,283,672,371 ms] noteScanEnd no scan source
,E/WifiStateMachine(  874): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@36b2f3c8 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  874): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  874): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  874): setDetailed state send new extra info0x
,I/CLocInfoService(  874): External Intent Received android.net.wifi.SCAN_RESULTS
,D/SecContentProvider2(  874): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  874): mCursor = null
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7775): MountEmulatedStorage()
I/libpersona( 7775): KNOX_SDCARD checking this for 10011
E/Zygote  ( 7775): v2
I/libpersona( 7775): KNOX_SDCARD not a persona
,I/wpa_supplicant( 1272): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1272): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine(  874): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  874): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,I/wpa_supplicant( 1272): Associated with C0.AA.48
,D/SecContentProvider2(  874): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  874): mCursor = null
I/ActivityManager(  874): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7775 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 1272): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1272): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  874): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  874): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  874): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  874): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  874): mCursor = null
,I/wpa_supplicant( 1272): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1272): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1272): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  874): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  874): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 1272): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1272): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1272): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1272): Blacklist: Clear (temp) 
I/wpa_supplicant( 1272): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/SELinux ( 7775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7775): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/WifiStateMachine(  874): Network connection established
D/WifiNative-HAL(  874): callSECApiVoid - ID [50]
E/WifiStateMachine(  874): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/CLocInfoService(  874): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  874): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  874): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  874): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  874): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  874): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  874): Got NetworkAgent Messenger
D/ConnectivityService(  874): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService(  874): updateNetworkInfo()
D/ConnectivityService(  874): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  874): NetworkAgent connected
,E/WifiStateMachine(  874): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  874): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  874): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  874): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  275): Setting iface cfg
,E/WifiStateMachine(  874): Start Dhcp Watchdog 2
,D/SecContentProvider2(  874): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  874): mCursor = null
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  874): calculateWifiScore() report new score 60
I/WifiStateMachine(  874): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  874): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  874): CMD_RSSI_POLL : out!
,D/ConnectivityService(  874): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,D/TimaKeyStoreProvider( 7775): TimaSignature is unavailable
,D/ActivityThread( 7775): Added TimaKeyStore provider
,E/WifiStateMachine(  874): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  874): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  874): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/ResourcesManager( 7775): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/ActivityManager(  874): Killing 6107:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/FOTA_Client( 7775): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7775): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7775): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7775): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7775): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/WifiStateMachine(  874): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/native  (  874): do suspend false
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2(  874): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  874): mCursor = null
,D/WifiP2pService(  874): InactiveState{ what=143375 }
D/WifiP2pService(  874): P2pEnabledState{ what=143375 }
,E/Zygote  ( 7797): MountEmulatedStorage()
E/Zygote  ( 7797): v2
I/libpersona( 7797): KNOX_SDCARD checking this for 10019
I/libpersona( 7797): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7797 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 6853:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,I/art     (  323): Explicit concurrent mark sweep GC freed 8744(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 280us total 11.869ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 7.907ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.750ms
,I/SELinux ( 7797): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  874): failed to open /acct/uid_10042/pid_6107/cgroup.procs: No such file or directory
,I/SELinux ( 7797): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7797): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7797): TimaSignature is unavailable
,D/ActivityThread( 7797): Added TimaKeyStore provider
,D/ResourcesManager( 7797): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,W/libprocessgroup(  874): failed to open /acct/uid_10045/pid_6853/cgroup.procs: No such file or directory
,I/KLMS-2.4.503: ( 7797): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7797): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452283672743
,I/KLMS-2.4.503: ( 7797): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
I/KLMS-2.4.503: ( 7797): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
I/KLMS-2.4.503: ( 7797): StateImplV2(): networkChangeListener().END
I/ActivityManager(  874): Killing 6877:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7812): MountEmulatedStorage()
E/Zygote  ( 7812): v2
I/libpersona( 7812): KNOX_SDCARD checking this for 10037
I/libpersona( 7812): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7812 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7812): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7812): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7812): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7812): TimaSignature is unavailable
,D/ActivityThread( 7812): Added TimaKeyStore provider
,E/dhcpcd  ( 7828): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/ResourcesManager( 7812): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/dhcpcd  ( 7828): version 5.5.6 starting
,E/dhcpcd  ( 7828): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,W/libprocessgroup(  874): failed to open /acct/uid_10051/pid_6877/cgroup.procs: No such file or directory
,I/SO_AGENT( 7812): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7835): MountEmulatedStorage()
,E/Zygote  ( 7835): v2
I/libpersona( 7835): KNOX_SDCARD checking this for 1000
I/libpersona( 7835): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7835 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  874): Killing 6896:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/dhcpcd  ( 7828): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7828): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7828): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7828): bssid match
,I/dhcpcd  ( 7828): wlan0: rebinding lease of 192.168.1.135
,I/SELinux ( 7835): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7835): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7835): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/TimaKeyStoreProvider( 7835): TimaSignature is unavailable
,D/ActivityThread( 7835): Added TimaKeyStore provider
,W/libprocessgroup(  874): failed to open /acct/uid_10058/pid_6896/cgroup.procs: No such file or directory
,D/ResourcesManager( 7835): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,I/dhcpcd  ( 7828): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/dhcpcd  ( 7828): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  874): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  874): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  874): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7861): MountEmulatedStorage()
I/libpersona( 7861): KNOX_SDCARD checking this for 10038
E/Zygote  ( 7861): v2
I/libpersona( 7861): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7861 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 6263:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SELinux ( 7861): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7861): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7861): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7861): TimaSignature is unavailable
,D/ActivityThread( 7861): Added TimaKeyStore provider
,W/libprocessgroup(  874): failed to open /acct/uid_1000/pid_6263/cgroup.procs: No such file or directory
D/ResourcesManager( 7861): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/SPPClientService( 7861): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7861): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7861): PushLog.txt file is not deleted.
D/SPPClientService( 7861): PushLog.txt file is not deleted.
,D/SPPClientService( 7861): ============PushLog. stop!
,E/SPPClientService( 7861): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7894): MountEmulatedStorage()
E/Zygote  ( 7894): v2
I/libpersona( 7894): KNOX_SDCARD checking this for 10045
I/libpersona( 7894): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7894 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 6638:com.sec.chaton/u0a86 (adj 15): bgCount ##41
,I/SELinux ( 7894): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7894): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7894): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/SMD     (  282): DCD ON
,E/WifiStateMachine(  874): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/SPPClientService( 7861): [[SystemStateMonitorService]] No Active Internet
,E/WifiStateMachine(  874): WifiStateMachine DHCP successful
D/WifiP2pService(  874): InactiveState{ what=143375 }
,D/WifiP2pService(  874): P2pEnabledState{ what=143375 }
E/WifiStateMachine(  874): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  874): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/ConnectivityService(  874): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  874): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  874): Not connected state, yet.
,E/WifiStateMachine(  874): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  874): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  874): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  874): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
,D/WifiNative-HAL(  874): callSECApiInt - ID [210]
E/WifiStateMachine(  874): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,D/PowerManagerService(  874): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  874): [s] DisplayPowerCallbacks : onStateChanged()
E/ConnectivityService(  874): updateNetworkInfo()
,D/ConnectivityService(  874): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  874): Adding iface wlan0 to network 503
,I/CLocInfoService(  874): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  874): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  874): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  874): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/lights  (  874): lcd : 4 +
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiWatchdogStateMachine.SingDnsChecker(  874): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  874): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/lights  (  874): lcd : 4 -
,E/WifiStateMachine(  874): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  874): Now, connected state.
E/WifiStateMachine(  874): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  874): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  874): evaluateTrafficStatsPolling
,I/CLocInfoService(  874): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
D/lights  (  874): lcd : 1 +
,E/WifiStateMachine(  874): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/TimaKeyStoreProvider( 7894): TimaSignature is unavailable
,I/WifiTrafficPoller(  874): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  874): mBoosterFLAG : 0
I/WifiTrafficPoller(  874): current booster mode : FullMode
,D/lights  (  874): lcd : 1 -
,D/ActivityThread( 7894): Added TimaKeyStore provider
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiNative-HAL(  874): callSECApiVoid - ID [212]
E/WifiStateMachine(  874): ConnectedState Enter  mScreenOn=true scanperiod=20000
,D/ConnectivityService(  874): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  874): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
I/CLocInfoService(  874): External Intent Received android.net.wifi.STATE_CHANGE
,I/WifiStateMachine(  874): REQUEST_POWER_SAVE_ON
,D/ConnectivityService(  874): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  874): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  874): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  874): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  275): QcRouteController
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/ResourcesManager( 7894): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,W/libprocessgroup(  874): failed to open /acct/uid_10086/pid_6638/cgroup.procs: No such file or directory
,V/        (  275): QcRouteController
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,V/        (  275): QcRouteController
,V/        (  275): QcRouteController
,I/SA      ( 7894): [SSP] onCreated
,V/        (  275): QcRouteController
,I/SA      ( 7894): [TPM] There is no property file
,I/SA      ( 7894): [SCU] isHaveSA() - false
,I/SA      ( 7894): [TPM] getModelProperty : null
,I/SA      ( 7894): [TPM] getCSCProperty : null
,V/        (  275): QcRouteController
,V/        (  275): QcRouteController
,I/SA      ( 7894): [DM] init START
,I/SA      ( 7894): [DM] This device is not a Vodafone
,W/ResourceType( 7894): Failure getting entry for 0x7f06000f (t=5 e=15) (error -75)
,W/ResourceType( 7894): Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
W/ResourceType( 7894): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 7894): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 7894): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 7894): Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
W/ResourceType( 7894): Failure getting entry for 0x7f060013 (t=5 e=19) (error -75)
,W/ResourceType( 7894): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7894): Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
W/ResourceType( 7894): Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,W/ResourceType( 7894): Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
W/ResourceType( 7894): Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,W/ResourceType( 7894): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 7894): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7894): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 7894): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 7894): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 7894): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 7894): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 7894): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,I/SA      ( 7894): [SCU] isHaveSA() - false
I/SA      ( 7894): support phone number id : false
,I/SA      ( 7894): [DM] init END
,V/        (  275): QcRouteController
I/SA      ( 7894): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7894): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 7894): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7894): [SLFUCHKMGR] constructor called
,D/ConnectivityService(  874): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  874): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/ConnectivityService(  874): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  874): calling update connectivity
D/ConnectivityService(  874): ignoring duplicate network state non-change
E/ConnectivityService(  874): updateNetworkInfo()
D/ConnectivityService(  874): ignoring duplicate network state non-change
E/ConnectivityService(  874): updateNetworkInfo()
,D/ConnectivityService(  874): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  874): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  874): calling update connectivity
,D/ConnectivityService(  874): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  874):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  874):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  874):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  874): currentScore = 0, newScore = 60
,D/ConnectivityService(  874):    accepting network in place of null
D/ConnectivityService(  874): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  874): Validated
,E/CSLegacyTypeTracker(  874): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker(  874): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  874): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 1455): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  874): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  874): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  874): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  874): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  874): getSBEnabled() enabled =false
D/SmartBondingService(  874): getSBEnabled() enabled =false
D/SmartBondingService(  874): getSBEnabled() enabled =false
,V/NetworkStats(  874): updateIfacesLocked()
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
V/NetworkStats(  874): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  874): UpdateStatsForKnox
D/EntConnectivity(  874): Not allowed due to - mEnabled false
D/ConnectivityService(  874): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): calling update connectivity
,D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/SmartBondingService(  874): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  874): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  874): Validated NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524290
V/NetworkStats(  874): performPollLocked() took 3ms
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
D/ConnectivityService(  874): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  874):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  874):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  874): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  874): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  874): calling update connectivity
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
V/NetworkStats(  874): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1173): updateDataNetType()
D/StatusBar.NetworkController( 1173): NoService, mRoamingIconId = 0
,D/ConnectivityService(  874): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524290
D/ConnectivityService(  874): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/StatusBar.NetworkController( 1173): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1173): updateDataNetType()
D/StatusBar.NetworkController( 1173): NoService, mRoamingIconId = 0
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
D/NtpTrustedTime(  874): currentTimeMillis() cache hit
I/SA      ( 7894): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7894): [OR] == isSIMCardReady false ==
D/StatusBar.NetworkController( 1173): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7894): [SCU] == networkStateCheck == true
I/SA      ( 7894): [DM] getCountryCodeFromCSC : DE
I/SA      ( 7894): isChinaCountryCode : false
I/SA      ( 7894): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7894): [OR] == networkStateCheck true ==
I/SA      ( 7894): [OR] GetMyCountryZoneTask
I/SA      ( 7894): [OR] onReceive END
I/SA      ( 7894): [SRS] prepareGetMyCountryZone
I/ActivityManager(  874): Killing 6919:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7894): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7894): [SSP] query invoked
I/SA      ( 7894): [TPMU] GetMccFromDB : null
I/SA      ( 7894): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7894): [TPM] isNoProxy(default) : true
,E/File    ( 7894): fail readDirectory() errno=2
D/accuweather( 7414): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 7414): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
D/accuweather( 7414): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7414): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7414): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7414): [KK AccuPhone]>>> RM:136 [0:0]  V init 
D/daemonapp( 1329): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/accuweather( 7414): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
D/daemonapp( 1329): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/accuweather( 7414): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
D/daemonapp( 1329): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
D/accuweather( 7414): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
D/accuweather( 7414): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7935): MountEmulatedStorage()
,E/Zygote  ( 7935): v2
I/libpersona( 7935): KNOX_SDCARD checking this for 1000
I/libpersona( 7935): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7935 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7935): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7935): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7935): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  874): failed to open /acct/uid_10098/pid_6919/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7935): TimaSignature is unavailable
,D/ActivityThread( 7935): Added TimaKeyStore provider
,D/ResourcesManager( 7935): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7935): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7935): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7935): premStatus:2
,I/KnoxUsageLogPro( 7935): isEulaShown : false
,I/KnoxUsageLogPro( 7935): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7950): MountEmulatedStorage()
E/Zygote  ( 7950): v2
I/libpersona( 7950): KNOX_SDCARD checking this for 10086
I/libpersona( 7950): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.NetStateReceiver: pid=7950 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 6975:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,I/SELinux ( 7950): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7950): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7950): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7950): TimaSignature is unavailable
,D/ActivityThread( 7950): Added TimaKeyStore provider
,D/ResourcesManager( 7950): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7950): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  874): failed to open /acct/uid_10033/pid_6975/cgroup.procs: No such file or directory
,D/PushModule( 7950): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 7950): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 7950): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 7950): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 7950): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  874): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 7950): [1][a] ChatONV isn't installed.
,D/ChatON  ( 7950): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7969): MountEmulatedStorage()
E/Zygote  ( 7969): v2
I/libpersona( 7969): KNOX_SDCARD checking this for 10088
I/libpersona( 7969): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7969 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 6951:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,I/SELinux ( 7969): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7969): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7969): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7969): TimaSignature is unavailable
,D/ActivityThread( 7969): Added TimaKeyStore provider
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  874): failed to open /acct/uid_10099/pid_6951/cgroup.procs: No such file or directory
,D/ConnectivityService(  874): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  874): MasterInitialState.processMessage what=3
,D/SmartBondingService(  874): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  874): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  874): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  874): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  874): CLocinfo wifi true 
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2188): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/SmartBondingService(  874): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  874): getSBEnabled() enabled =false
D/SmartBondingService(  874): getSBEnabled() enabled =false
D/SmartBondingService(  874): getSBEnabled() enabled =false
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  874): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3811): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3811): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/SystemBroadcastReceiver( 7203): [#DCM#] [DCM_Performance] onReceive completed in time  1662 microsec. 
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7203): [#DCM#] Calling notifyListeners. 
I/DCMController( 7203): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7203): [#DCM#] setIsConnectedForExtractors 
,W/ContextImpl( 2210): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 2210): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DatabaseRebuilderTask( 7203): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5395): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/FrameworkService( 7203): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7203): [#DCM#] onCreate FrameworkService end 
,I/DCMConfig( 7203): [#DCM#] getSuccessState = true
,I/FrameworkService( 7203): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
I/IntentHandler( 7203): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  874): mCursor = null
,I/SystemUtils( 7203): [#DCM#] LM: false,AM:690393088
,I/DCMThreadPoolExecutor( 7203): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7203): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@20eb25f1 is submitted
I/FrameworkService( 7203): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 31656 mirosec. 
,I/DatabaseRebuilderTask( 7203): [#DCM#] createLuceneReader done 
I/DatabaseRebuilderTask( 7203): [#DCM#] resyncLocation   
I/DatabaseRebuilderTask( 7203): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
,I/DatabaseRebuilderTask( 7203): [#DCM#] topDocs hits = 0
I/DatabaseRebuilderTask( 7203): [#DCM#] No of Location data to be added:  0
,I/DatabaseRebuilderTask( 7203): [#DCM#] releaseLuceneReader done 
I/DatabaseRebuilderTask( 7203): [#DCM#] Starting media manager do operation 
I/SystemUtils( 7203): [#DCM#] setHeavySharedPref set as  false
,I/IntentHandler( 7203): [#DCM#] Stopping service with ids up to  1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,I/DCMThreadPoolExecutor( 7203): [#DCM#] afterExecute FutureTask
,I/DCMController( 7203): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@20eb25f1
,I/SA      ( 7894): [RC New] Execute method=[GET] start
,I/ActivityManager(  874): Killing 7018:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,D/Headlines( 5524): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5524): getCountryCode(): countryCode = DE
,D/Headlines( 5524): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5524): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5524): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5524): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5524): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5524): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5524): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,I/SA      ( 7894): [RC New] Security=[true]
,I/System.out( 7894): Thread-1295(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,E/Zygote  ( 7987): MountEmulatedStorage()
E/Zygote  ( 7987): v2
I/libpersona( 7987): KNOX_SDCARD checking this for 10128
,I/libpersona( 7987): KNOX_SDCARD not a persona
,I/System.out( 7894): Thread-1295(ApacheHTTPLog):isShipBuild true
,I/ActivityManager(  874): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7987 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/System.out( 7894): Thread-1295(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
I/SELinux ( 7987): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7987): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7987): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  874): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  874): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  874): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  874): identical MTU - not setting
,D/ConnectivityService(  874): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  874): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
E/WifiStateMachine(  874): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
V/        (  275): QcRouteController
,D/SmartBondingService(  874): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  874): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  874): getSBEnabled() enabled =false
D/SmartBondingService(  874): getSBEnabled() enabled =false
D/SmartBondingService(  874): getSBEnabled() enabled =false
,D/TimaKeyStoreProvider( 7987): TimaSignature is unavailable
,D/ActivityThread( 7987): Added TimaKeyStore provider
,V/        (  275): QcRouteController
,W/NetworkManagementService(  874): route cmd failed: 
W/NetworkManagementService(  874): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  874): '
W/NetworkManagementService(  874): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  874): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  874): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  874): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  874): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  874): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  874): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  874): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  874): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  874): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  874): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  874): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  874): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  874): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  874): calling update connectivity
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  874): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  874): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  874): calling update connectivity
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  874): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524295
,W/libprocessgroup(  874): failed to open /acct/uid_10003/pid_7018/cgroup.procs: No such file or directory
D/ResourcesManager( 7987): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7987): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7987): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7987): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7987): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  874): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/WebViewFactory( 7987): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7987): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7987): Loading: webviewchromium
,I/LibraryLoader( 7987): Time to load native libraries: 5 ms (timestamps 1661-1666)
I/LibraryLoader( 7987): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7987): Binding Chromium to main looper Looper (main, tid 1) {3818490d}
,I/LibraryLoader( 7987): Expected native library version number "",actual native library version number ""
,I/chromium( 7987): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7987): Initializing chromium process, renderers=0
,W/art     ( 7987): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7987): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7987): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7987): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7987): Requires BLUETOOTH permission
,I/Adreno-EGL( 7987): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7987): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7987): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7987): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7987): Remote Branch: 
I/Adreno-EGL( 7987): Local Patches: 
I/Adreno-EGL( 7987): Reconstruct Branch: 
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4266, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  874): Plugged
I/MotionRecognitionService(  874): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/NSApplication( 7987): Starting up...
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8051): MountEmulatedStorage()
,E/Zygote  ( 8051): v2
I/libpersona( 8051): KNOX_SDCARD checking this for 10138
I/libpersona( 8051): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8051 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 7024:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,I/SELinux ( 8051): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8051): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8051): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8051): TimaSignature is unavailable
,D/ActivityThread( 8051): Added TimaKeyStore provider
,W/libprocessgroup(  874): failed to open /acct/uid_10020/pid_7024/cgroup.procs: No such file or directory
,D/ResourcesManager( 8051): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 8051): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8051): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8051): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,D/QuickConnect( 8051): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8051): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8051): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8066): MountEmulatedStorage()
E/Zygote  ( 8066): v2
I/libpersona( 8066): KNOX_SDCARD checking this for 10163
I/libpersona( 8066): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8066 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 7050:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,I/SA      ( 7894): [RC New] [v2liruge] api execute + 705
,I/SA      ( 7894): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 7894): AsyncTask #1 calls detatch()
,I/SA      ( 7894): [ODM] saveOpenData( GEO_IP, PL )
,I/SELinux ( 8066): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8066): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8066): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SA      ( 7894): [OCP] update openData : PL
,I/SA      ( 7894): [TPMU] getNetworkMcc : 
,D/TimaKeyStoreProvider( 8066): TimaSignature is unavailable
,D/ActivityThread( 8066): Added TimaKeyStore provider
,I/SA      ( 7894): [SCU] saveMccToPreferece Start
,I/SA      ( 7894): [SCU] RegionMCC : 260
I/SA      ( 7894): [SSP] query invoked
,I/SA      ( 7894): [TPMU] GetMccFromDB : null
,I/SA      ( 7894): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7894): [SCU] saveMccToPreferece End
,I/SA      ( 7894): [RC New] executeRequest [v2liruge] end. 790
I/SA      ( 7894): [RC New] Execute end
,I/SA      ( 7894): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7894): [OR] GetMyCountryZoneTask Success
,D/ResourcesManager( 8066): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8066): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8066): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8066): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8066): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  874): failed to open /acct/uid_1000/pid_7050/cgroup.procs: No such file or directory
,D/RCPManagerService(  874): exchangeData() failure , invalid userId
,D/RCPManagerService(  874): exchangeData() failure , invalid userId
,D/RCPManagerService(  874): exchangeData() failure , invalid userId
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
D/RCPManagerService(  874): exchangeData() failure , invalid userId
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8089): MountEmulatedStorage()
,I/ActivityManager(  874): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8089 uid=10078 gids={50078, 9997} abi=armeabi-v7a
E/Zygote  ( 8089): v2
I/libpersona( 8089): KNOX_SDCARD checking this for 10078
I/libpersona( 8089): KNOX_SDCARD not a persona
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/art     (  323): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 1.416ms total 14.050ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 253us total 7.748ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.969ms
,I/SELinux ( 8089): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8089): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8089): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  874): exchangeData() failure , invalid userId
,D/RCPManagerService(  874): exchangeData() failure , invalid userId
V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,D/SecurityLogAgent( 7648): KnoxConfiguration : Current State = 1
V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,D/SecurityLogAgent( 7648): KnoxConfiguration : Current State Mapping Found 
V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,D/SecurityLogAgent( 7648): StateMachine : Current State = 1
V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,D/SecurityLogAgent( 7648): StateMachine : Changed Current State = 1
V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,I/ActivityManager(  874): Killing 7067:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,D/TimaKeyStoreProvider( 8089): TimaSignature is unavailable
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
D/ActivityThread( 8089): Added TimaKeyStore provider
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/ActivityManager(  874): Killing 7084:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
D/com.peel.receiver.ConnectivityActionReceiver( 5628): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 5628): 
D/com.peel.receiver.ConnectivityActionReceiver( 5628): 
D/com.peel.receiver.ConnectivityActionReceiver( 5628): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5628): 
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 5628): 
D/com.peel.receiver.ConnectivityActionReceiver( 5628): 
D/com.peel.receiver.ConnectivityActionReceiver( 5628):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5628): 
V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
D/com.peel.receiver.ConnectivityActionReceiver( 5628): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5628): 
D/com.peel.receiver.ConnectivityActionReceiver( 5628): 
D/com.peel.receiver.ConnectivityActionReceiver( 5628): last run: 1452283589907 -- System.currentTimeMillis()-last_run: 85123
,D/com.peel.receiver.ConnectivityActionReceiver( 5628): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5628): ... skip last_72_check
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 8089): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,E/Zygote  ( 8106): MountEmulatedStorage()
I/libpersona( 8106): KNOX_SDCARD checking this for 10178
E/Zygote  ( 8106): v2
I/libpersona( 8106): KNOX_SDCARD not a persona
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,I/ActivityManager(  874): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8106 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,I/SELinux ( 8106): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8106): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8106): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,D/BadgeProvider( 8089): onCreate
D/BadgeProvider( 8089): DatabaseHelper
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
D/TimaKeyStoreProvider( 8106): TimaSignature is unavailable
V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,D/ActivityThread( 8106): Added TimaKeyStore provider
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
D/ResourcesManager( 8106): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 8066): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,W/libprocessgroup(  874): failed to open /acct/uid_10112/pid_7067/cgroup.procs: No such file or directory
,W/libprocessgroup(  874): failed to open /acct/uid_10118/pid_7084/cgroup.procs: No such file or directory
,I/art     (  874): Explicit concurrent mark sweep GC freed 64282(3MB) AllocSpace objects, 5(80KB) LOS objects, 30% free, 36MB/52MB, paused 1.359ms total 83.582ms
,D/BadgeProvider( 8089): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager(  874): Killing 7100:com.samsung.helphub/1000 (adj 15): bgCount ##41
,D/BadgeProvider( 8089): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 8089): sendNotify, [notify] : null
D/BadgeProvider( 8089): update, [uri] : content://com.sec.badge/apps/1
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BadgeProvider( 8089): update, [BadgeCount] : badgecount=0
D/Launcher.Model( 1462): reloadBadges entered.
D/BadgeProvider( 8089): update, [UpdateCount] : 1
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,D/ChimeraCfgMgr( 2407): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2407): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager(  874): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7178): notifyNetworkActivated
,W/libprocessgroup(  874): failed to open /acct/uid_1000/pid_7100/cgroup.procs: No such file or directory
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 7178): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  874): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2407): [AccountUtils] Account not ready
W/Kids    ( 2407): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2407): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2407): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2407): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2407): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2407): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2407): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2407): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2407): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2407): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2407): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2407): 	at java.lang.Thread.run(Thread.java:818)
D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7178): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7178): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7178): exit::IDLE
D/InitializeManagerStateMachine( 7178): entry::NETWORK_CHECK
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7178): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7178): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7178): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7178): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7178): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7178): entry::SUCCESS
D/hcjo    ( 7178): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1299): Starting #8
I/Hs20UtilService( 1299): Message received 5007
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1299): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1299): MountReceiver.onReceive - Keep current state
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,D/hcjo    ( 7178): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7178): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Hs20UtilService( 1299): Starting #9
,I/Hs20UtilService( 1299): Message received 5007
D/InitializeManagerStateMachine( 7178): exit::SUCCESS
,D/InitializeManagerStateMachine( 7178): entry::IDLE
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1299): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1299): Starting #10
,I/Hs20UtilService( 1299): Message received 5007
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1299): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1299): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1299): Starting #11
,I/Hs20UtilService( 1299): Message received 5007
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1299): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  874): callSECApi what=220
D/WifiStateMachine(  874): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 7718): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7718): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7718): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7718): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/DIAGMON_AGENT( 7756): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7756): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService(  874): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=874
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  874): [s] DisplayPowerCallbacks : onStateChanged()
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/lights  (  874): lcd : 6 +
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  874): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/lights  (  874): lcd : 6 -
,D/lights  (  874): lcd : 8 +
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/lights  (  874): lcd : 8 -
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,I/FOTA_Client( 7775): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7775): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7775): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7775): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7775): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/KLMS-2.4.503: ( 7797): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7797): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452283675592
,I/KLMS-2.4.503: ( 7797): MainReciver(): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/KLMS-2.4.503: ( 7797): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7797): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7797): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7797): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/SO_AGENT( 7812): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7861): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7894): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/SA      ( 7894): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7894): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7894): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7894): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7894): [SCU] == networkStateCheck == true
I/SA      ( 7894): [DM] getCountryCodeFromCSC : DE
I/SA      ( 7894): isChinaCountryCode : false
I/SA      ( 7894): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7894): [OR] == networkStateCheck true ==
I/SA      ( 7894): [OR] GetMyCountryZoneTask
,I/SA      ( 7894): [OR] onReceive END
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7894): [SRS] prepareGetMyCountryZone
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/accuweather( 7414): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7414): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 7894): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7894): [SSP] query invoked
,I/KnoxUsageLogPro( 7935): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7935): premStatus:2
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/KnoxUsageLogPro( 7935): isEulaShown : false
I/KnoxUsageLogPro( 7935): KnoxUsageReceiver onReceive : not Processible, just return
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/Headlines( 5524): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5524): getCountryCode(): countryCode = DE
,D/Headlines( 5524): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5524): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5524): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5524): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5524): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5524): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5524): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/SA      ( 7894): [TPMU] GetMccFromDB : null
I/SA      ( 7894): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7894): [TPM] isNoProxy(default) : true
,D/GCM     ( 1638): Connected
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7894): [RC New] Execute method=[GET] start
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/QuickConnect( 8051): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/GCM     ( 1638): Message class com.google.f.a.a.p
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/QuickConnect( 8051): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8051): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  874): exchangeData() failure , invalid userId
,D/RCPManagerService(  874): exchangeData() failure , invalid userId
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7648): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7648): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7648): StateMachine : Current State = 1
D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7648): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5628): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5628): 
D/com.peel.receiver.ConnectivityActionReceiver( 5628): 
D/com.peel.receiver.ConnectivityActionReceiver( 5628): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5628): 
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 5628): 
D/com.peel.receiver.ConnectivityActionReceiver( 5628): 
D/com.peel.receiver.ConnectivityActionReceiver( 5628):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5628): 
D/com.peel.receiver.ConnectivityActionReceiver( 5628): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5628): 
D/com.peel.receiver.ConnectivityActionReceiver( 5628): 
D/com.peel.receiver.ConnectivityActionReceiver( 5628): last run: 1452283589907 -- System.currentTimeMillis()-last_run: 85863
D/com.peel.receiver.ConnectivityActionReceiver( 5628): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5628): ... skip last_72_check
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1173): value : false
,D/ChimeraCfgMgr( 2407): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7178): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7178): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7178): exit::IDLE
D/InitializeManagerStateMachine( 7178): entry::NETWORK_CHECK
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7178): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7178): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7178): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7178): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7178): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7178): entry::SUCCESS
D/hcjo    ( 7178): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7178): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7178): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7178): exit::SUCCESS
D/InitializeManagerStateMachine( 7178): entry::IDLE
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2407): [AccountUtils] Account not ready
W/Kids    ( 2407): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2407): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2407): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2407): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2407): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2407): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2407): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2407): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2407): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2407): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2407): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2407): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/SA      ( 7894): [RC New] Security=[true]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/SMD     (  282): DCD ON
,E/Watchdog(  874): !@Sync 3
,W/ProcessCpuTracker(  874): Skipping unknown process pid 8048
W/ProcessCpuTracker(  874): Skipping unknown process pid 8049
,W/ProcessCpuTracker(  874): Skipping unknown process pid 8105
,W/ProcessCpuTracker(  874): Skipping unknown process pid 8140
W/ProcessCpuTracker(  874): Skipping unknown process pid 8141
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/SA      ( 7894): [RC New] [v2liruge] api execute + 642
I/SA      ( 7894): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7894): AsyncTask #2 calls detatch()
,I/SA      ( 7894): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7894): [OCP] update openData : PL
,I/SA      ( 7894): [TPMU] getNetworkMcc : 
,I/SA      ( 7894): [SCU] saveMccToPreferece Start
I/SA      ( 7894): [SCU] RegionMCC : 260
I/SA      ( 7894): [SSP] query invoked
,I/SA      ( 7894): [TPMU] GetMccFromDB : null
I/SA      ( 7894): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7894): [SCU] saveMccToPreferece End
,I/SA      ( 7894): [RC New] executeRequest [v2liruge] end. 844
I/SA      ( 7894): [RC New] Execute end
,I/SA      ( 7894): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7894): [OR] GetMyCountryZoneTask Success
,I/WifiStateMachine(  874): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  874): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7828): wlan0: sending IPv6 Router Solicitation
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,V/AlarmManager(  874): waitForAlarm result :8
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1638): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,W/Search.LoginHelper( 1556): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7586): Test app app.js loaded
I/jxcore-log( 7586): 
,I/chromium( 7586): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 7586): Skipped 439 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7586): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  874): CMD_RSSI_POLL : out!
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/PowerManagerService(  874): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 874) eventTime = 106264
,D/PowerManagerService(  874): [s] UserActivityState : 2 -> 1
,D/PowerManagerService(  874): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=874 (0x0)
D/PowerManagerService(  874): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=874, ws=WorkSource{10059}) (elapsedTime=3500)
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/SMD     (  282): DCD ON
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/GAV4    ( 7987): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/SurfaceFlinger(  249): id=16 Removed Toast (8/8)
,I/SurfaceFlinger(  249): id=16 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,V/AlarmManager(  874): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  874): SIOP:: AP = 410, PST = 417, CUR = 300
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/Atfwd_Sendcmd(  330): AtCmdFwd service not ready - Exhausted retry attempts - :6
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/Atfwd_Daemon(  330): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7718): mConnectivityHandler : connected
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7718): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 7718): ================================================
I/CSTORAGE( 7718):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 7718): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7718): [GetString-S]
E/art     ( 7718): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 7718): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7718): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7718): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7718): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7718): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7718): [ensureRegistration] - No Samsung account
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness(),
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7828): wlan0: sending IPv6 Router Solicitation
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore in!,
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  874): CMD_RSSI_POLL : out!
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/SMD     (  282): DCD ON
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness(),
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  874): CMD_RSSI_POLL : out!
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7828): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7828): wlan0: no IPv6 Routers available
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/SMD     (  282): DCD ON
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,V/BitmapFactory( 1173): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_out.png
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7178): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7178): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7178): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7178): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
D/hcjo    ( 7178): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7178): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7178): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7178): entry::IDLE
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 7178): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 7178): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7178): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 7178): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 7178): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7178): exit::CHECK_TIMEOUT_FOR_UPDATE,
D/PreloadUpdateManagerStateMachine( 7178): entry::IDLE,
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  874): CMD_RSSI_POLL : out!
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/SMD     (  282): DCD ON
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/FactoryTest( 6534): Not factory mode
,D/FactoryTest( 6534): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6534): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6534): still no open session command from host, so toast
,W/ContextImpl( 6534): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6534): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6534): Timeline: Activity_launch_request id:com.android.settings time:115810
,E/PersonaManagerService(  874): inState():  stateMachine is null !!
E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  874): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  874): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 874  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  874): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/SQLiteSecureOpenHelper( 3560): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3560): getDatabaseLocked(b,b,pwd)...
,E/MTPRx   ( 6534): started activity for popup
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/ResourcesManager( 6534): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6534): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6534): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6534): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6534): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6534): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6534): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6534): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,E/ActivityManager(  874): Invalid thumbnail dimensions: 576x576
,D/InputMethodManagerService(  874): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  874): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@21e5801c attribute=null, token = android.os.BinderProxy@2727d221
,I/SQLiteSecureOpenHelper( 3560): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3560): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6534): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6534): dev.kiessupport is : TRUE
,D/Activity( 6534): performCreate Call secproduct feature valuefalse
D/Activity( 6534): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/ActivityManager(  874): post active user change for 0
D/KnoxTimeoutHandler(  874): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  874): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/Timeline( 7586): Timeline: Activity_idle id: android.os.BinderProxy@3b850668 time:116068
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  874): SIOP:: AP = 350, PST = 406, CUR = 300
,D/X       (  874): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1219):  LEVEL : -1
,I/SystemBroadcastReceiver( 7203): [#DCM#] [DCM_Performance] onReceive completed in time  1895 microsec. 
,E/TranscodeReceiver( 7269): onReceive : android.intent.action.CHECK_SIOP_LEVEL
D/TranscodeReceiver( 7269):  SIOP_LEVEL: -1
,I/SystemBroadcastReceiver( 7203): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7203): [#DCM#] onReceive action = EVENT_SIOP
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  874): CMD_RSSI_POLL : out!
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/SMD     (  282): DCD ON
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  874): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 874  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  874): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  874): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 874  pkgName : ACTIVITY_RESUME_BOOSTER@10
,V/AlarmManager(  874): waitForAlarm result :4
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  874): Plugged
I/MotionRecognitionService(  874): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CustomFrequencyManagerService(  874): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 874  tag : ACTIVITY_RESUME_BOOSTER@10
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1638): Explicit concurrent mark sweep GC freed 33573(2028KB) AllocSpace objects, 22(1782KB) LOS objects, 39% free, 17MB/29MB, paused 709us total 54.548ms
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/Finsky  ( 6703): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6703): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6703): [1] 5.onFinished: Scheduling replication attempt 3.
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  874): CMD_RSSI_POLL : out!
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/SMD     (  282): DCD ON
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,V/AlarmManager(  874): waitForAlarm result :4
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness(),
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness(),
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8,
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness(),
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  874): CMD_RSSI_POLL : out!
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/SMD     (  282): DCD ON
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  874): CMD_RSSI_POLL : out!
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,E/SMD     (  282): DCD ON
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  874): SIOP:: AP = 330, PST = 392, CUR = 300
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 2
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  874): Plugged
I/MotionRecognitionService(  874): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8,
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  874): CMD_RSSI_POLL : out!
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  874): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  874): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  874): lcd : 1 +
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,D/lights  (  874): lcd : 1 -
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/SMD     (  282): DCD ON
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  874): CMD_RSSI_POLL : out!
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/SMD     (  282): DCD ON
,E/Watchdog(  874): !@Sync 4
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
,D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,D/StatusBar.NetworkController( 1173): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): applyOpen
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  874): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  874): CMD_RSSI_POLL : out!
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  874): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  874): Nap time (uid 1000)...
I/PowerManagerService(  874): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  874): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  874): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  874): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI(  874): setDeviceInteractive: 0
,D/PowerManagerService(  874): handleSandman : startDream()
,D/InputManager-JNI(  874): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,E/PowerManagerService(  874): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  874): Sleeping (uid 1000)...
D/PowerManagerService(  874): [s] UserActivityState : 4 -> 0
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/PowerManagerService(  874): [input device light] setInputDeviceLightOn is called : 0
,D/InputManager-JNI(  874): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/PowerManagerService(  874): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  874): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  874): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  874): 	.unregisterCallback : 1, client=
,D/SContextService(  874): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3bdc7ebb, Service = Auto Rotation, used = 1
,W/CAE     (  874): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  874): stop(ContextProvider.java:149)
,V/CAE     (  874): clear(AutoRotationRunner.java:182)
,V/CAE     (  874): disable(AutoRotationRunner.java:171)
,I/CAE     (  874): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  874): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  296): sendContextData: -78, 7, 0, 0
,D/CAE     (  874): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  874): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  874): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  874): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  874): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  874): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  874): removeSContextService() : service = Auto Rotation
D/SContextService(  874): ===== SContext Service List =====
D/SContextManager(  874):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@30d2cd89, service=Auto Rotation
,D/KeyguardViewMediator( 1173): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1173): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1173): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1173): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/KeyguardViewMediator( 1173): timeout : 5000
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/DisplayPowerController(  874): ColorFade: onAnimationStart
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 0
,D/lights  (  874): lcd : 0 +
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 0
,I/SQLiteSecureOpenHelper( 3560): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3560): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 1173): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1173): handleNotifyScreenOff
,D/LightsService(  874): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 874) 
D/LightsService(  874): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  874): [SvcLED]  onSensorChanged::light value = 0
,D/lights  (  874): lcd : 0 -
,D/SensorManager(  874): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  874): unregisterListener ::   
D/lights  (  874): led_pattern : 5 +
,D/BatteryService(  874): turn on LED for fully charged
,D/lights  (  874): led_pattern : 5 -
,D/LightsService(  874): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  874): handleMessage(CaPowerManager.java:182) - AP_SLEEP
I/CAE     (  874): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  874): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  874): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  296): sendContextData: -76, 13, -46, 0
,I/CAE     (  874): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 20, 8, 29,
,D/SensorHubManager(  874): SendSensorHubData: send data = -63, 14, 20, 8, 29
D/Sensorhubs(  296): sendContextData: -63, 14, 20, 8, 29
,E/LightSensor(  874): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  874): mCallbacks.updateBrightness()
D/DisplayPowerController(  874): getFinalBrightness : 8 -> 0
,E/SMD     (  282): DCD ON
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  874):  handler : SCREEN_OFF end 
,D/NotificationService(  874): ACTION_SCREEN_OFF
,D/LightsService(  874): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 874) 
D/LightsService(  874): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  874): [SvcLED]  onSensorChanged::light value = 0
,D/WifiStateMachine(  874): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  874): handleScreenStateChanged Exit: false
,D/SensorManager(  874): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  874): unregisterListener ::   
D/LightsService(  874): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,E/WifiStateMachine(  874): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  874): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/native  (  874): do suspend true
,D/audio_hw_primary(  290): adev_set_parameters: enter: screen_state=off
V/voice   (  290): voice_set_parameters: enter: screen_state=off
V/voice   (  290): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  290): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  290): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  290): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  290): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  874): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  874): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  874): Bridge Server is not available
,D/VolumePanel( 1173): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 1173): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1173): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1173): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  874): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  874): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1449): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1173):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1173): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1173): dismissHelpPopup 
,D/accuweather( 2188): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2188): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2188): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/SystemBroadcastReceiver( 7203): [#DCM#] [DCM_Performance] onReceive completed in time  1211 microsec. 
,D/DisplayPowerState(  874): !@ ColorFade entry
D/DisplayPowerController(  874): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  874): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  874): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  874): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/AutomaticBrightnessController(  874): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  874): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,I/SystemBroadcastReceiver( 7203): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7203): [#DCM#] onReceive action = EVENT_SCREEN_OFF
,I/DCMController( 7203): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/SensorManager(  874): unregisterListener ::   
,E/Sensors (  874): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,W/ActivityManager(  874): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  874): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  874): [PWL] sb release: PowerManagerService.Broadcasts
,D/DisplayPowerController(  874): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  874): getFinalBrightness : 0 -> 0
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
I/DisplayManagerService(  874): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  874): Display changed displayId=0
,D/SensorManager(  874): unregisterListener ::   
,D/SSRM:m  (  874): SIOP:: AP = 320, PST = 376, CUR = 300
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/StatusBar.NetworkController( 1173): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,I/rmt_storage(  271): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
I/rmt_storage(  271): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  271): wakelock acquired: 1, error no: 42
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 22
I/rmt_storage(  271): 
,I/rmt_storage(  271): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  874): Excessive delay in setPowerMode(): 255ms
D/PowerManagerService(  874): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/MISC PowerHAL(  874): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  874): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  874): Got set_interactive hint
,I/PowerManagerService(  874): [PWL] Off : 0s ago
,I/PowerManagerService(  874): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  874): [PWL]     mDisplayReady : false
D/DisplayPowerController(  874): getFinalBrightness : 0 -> 0
,D/PowerManagerService(  874): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  874): [PWL] sb release: PowerManagerService.Display
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,V/AlarmManager(  874): waitForAlarm result :4
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6703): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6703): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6703): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,V/AlarmManager(  874): waitForAlarm result :4
,D/KeyguardViewMediator( 1173): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/KeyguardViewMediator( 1173): doKeyguard: not showing because lockscreen is off
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/PowerManagerService(  874): [PWL] Off : 5s ago
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  874): SIOP:: AP = 320, PST = 365, CUR = 300,
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  874): [PWL] Off : 15s ago
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,V/AlarmManager(  874): waitForAlarm result :4
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  874): stay LED for fully charged
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
I/MotionRecognitionService(  874): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1638): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/HttpOperation( 6672): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6672): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6672): 	at kfv.a(PG:65)
E/HttpOperation( 6672): 	at kff.u(PG:385)
E/HttpOperation( 6672): 	at kfb.a(PG:29)
E/HttpOperation( 6672): 	at kff.l(PG:132)
E/HttpOperation( 6672): 	at dsf.a(PG:807)
E/HttpOperation( 6672): 	at fhk.a(PG:1126)
E/HttpOperation( 6672): 	at fhk.a(PG:908)
E/HttpOperation( 6672): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6672): 	at ihi.a(PG:22)
E/HttpOperation( 6672): 	at kft.a(PG:91)
E/HttpOperation( 6672): 	at kfv.a(PG:62)
E/HttpOperation( 6672): 	... 8 more
E/HttpOperation( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6672): 	at gde.c(Unknown Source)
E/HttpOperation( 6672): 	at gde.b(Unknown Source)
E/HttpOperation( 6672): 	at ihi.a(PG:19)
E/HttpOperation( 6672): 	... 10 more
,I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,D/SSRM:m  (  874): SIOP:: AP = 310, PST = 356, CUR = 300
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,E/HttpOperation( 6672): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6672): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6672): 	at kfv.a(PG:65)
E/HttpOperation( 6672): 	at kff.u(PG:385)
E/HttpOperation( 6672): 	at kfb.a(PG:29)
E/HttpOperation( 6672): 	at kff.l(PG:132)
E/HttpOperation( 6672): 	at ieo.a(PG:43)
E/HttpOperation( 6672): 	at iep.a(PG:93)
E/HttpOperation( 6672): 	at fhn.a(PG:59)
E/HttpOperation( 6672): 	at lex.a(PG:85)
E/HttpOperation( 6672): 	at lex.b(PG:132)
E/HttpOperation( 6672): 	at fhk.a(PG:1146)
E/HttpOperation( 6672): 	at fhk.a(PG:908)
E/HttpOperation( 6672): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6672): 	at ihi.a(PG:22)
E/HttpOperation( 6672): 	at kft.a(PG:91)
E/HttpOperation( 6672): 	at kfv.a(PG:62)
E/HttpOperation( 6672): 	... 12 more
E/HttpOperation( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6672): 	at gde.c(Unknown Source)
E/HttpOperation( 6672): 	at gde.b(Unknown Source)
E/HttpOperation( 6672): 	at ihi.a(PG:19)
E/HttpOperation( 6672): 	... 14 more
,E/SQLiteLog( 1638): (10) POSIX Error : 11 SQLite Error : 3850
,E/ExperimentLoader( 6672): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6672): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6672): 	at kfv.a(PG:65)
E/ExperimentLoader( 6672): 	at kff.u(PG:385)
E/ExperimentLoader( 6672): 	at kfb.a(PG:29)
E/ExperimentLoader( 6672): 	at kff.l(PG:132)
E/ExperimentLoader( 6672): 	at ieo.a(PG:43)
E/ExperimentLoader( 6672): 	at iep.a(PG:93)
E/ExperimentLoader( 6672): 	at fhn.a(PG:59)
E/ExperimentLoader( 6672): 	at lex.a(PG:85)
E/ExperimentLoader( 6672): 	at lex.b(PG:132)
E/ExperimentLoader( 6672): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6672): 	at fhk.a(PG:908)
E/ExperimentLoader( 6672): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6672): 	at ihi.a(PG:22)
E/ExperimentLoader( 6672): 	at kft.a(PG:91)
E/ExperimentLoader( 6672): 	at kfv.a(PG:62)
E/ExperimentLoader( 6672): 	... 12 more
E/ExperimentLoader( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6672): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6672): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6672): 	at ihi.a(PG:19)
E/ExperimentLoader( 6672): 	... 14 more
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6672): [getaccountstatus] Unexpected exception
E/HttpOperation( 6672): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6672): 	at kfv.a(PG:65)
E/HttpOperation( 6672): 	at kff.u(PG:385)
E/HttpOperation( 6672): 	at kfb.a(PG:29)
E/HttpOperation( 6672): 	at ixd.a(PG:248)
E/HttpOperation( 6672): 	at ixd.b(PG:206)
E/HttpOperation( 6672): 	at ixd.a(PG:175)
E/HttpOperation( 6672): 	at fig.a(PG:78)
E/HttpOperation( 6672): 	at lex.a(PG:85)
E/HttpOperation( 6672): 	at lex.b(PG:132)
E/HttpOperation( 6672): 	at fhk.a(PG:1146)
E/HttpOperation( 6672): 	at fhk.a(PG:908)
E/HttpOperation( 6672): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6672): 	at ihi.a(PG:22)
E/HttpOperation( 6672): 	at kft.a(PG:91)
E/HttpOperation( 6672): 	at kfv.a(PG:62)
E/HttpOperation( 6672): 	... 12 more
E/HttpOperation( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6672): 	at gde.c(Unknown Source)
E/HttpOperation( 6672): 	at gde.b(Unknown Source)
E/HttpOperation( 6672): 	at ihi.a(PG:19)
E/HttpOperation( 6672): 	... 14 more
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/EsSyncAdapterService( 6672): Sync failure
E/EsSyncAdapterService( 6672): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6672): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6672): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6672): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6672): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6672): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6672): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6672): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6672): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6672): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6672): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6672): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6672): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6672): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6672): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6672): 	... 10 more
E/EsSyncAdapterService( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6672): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6672): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6672): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6672): 	... 12 more
E/EsSyncAdapterService( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6672): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6672): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6672): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6672): 	... 14 more
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  874): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 156155, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/art     (  874): Explicit concurrent mark sweep GC freed 69573(4MB) AllocSpace objects, 29(3MB) LOS objects, 30% free, 36MB/52MB, paused 7.217ms total 269.042ms
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  874): mCursor = null
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SQLiteLog( 1638): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,V/AlarmManager(  874): waitForAlarm result :4
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6703): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6703): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6703): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  282): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  282): DCD ON
,E/Watchdog(  874): !@Sync 5
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  874): SIOP:: AP = 310, PST = 347, CUR = 300
,I/PowerManagerService(  874): [PWL] Off : 30s ago
,V/AlarmManager(  874): waitForAlarm result :8
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/BatteryService(  874): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  874): SIOP:: AP = 300, PST = 337, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  874): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1638): Vacuum at: now=1452283753290 tag=VacuumService
,I/GoogleURLConnFactory( 1638): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png,
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1638): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1638): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1638): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1638): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1638): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1638): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1638): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1638): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1638): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1638): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,I/System.out( 1638): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1638): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1638): (HTTPLog)-Thread-193-832785738: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1638): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1638, getuid(): 10012
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 1638): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1638, getuid(): 10012
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6703): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6703): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6703): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1638): No account for auth token provided
,I/qtaguid ( 1638): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1638, getuid(): 10012
,W/Uploader( 1638): No account for auth token provided
,I/qtaguid ( 1638): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1638, getuid(): 10012
,W/Uploader( 1638): No account for auth token provided
,I/qtaguid ( 1638): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1638, getuid(): 10012
,W/Uploader( 1638): No account for auth token provided
,I/qtaguid ( 1638): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1638, getuid(): 10012
,E/SMD     (  282): DCD ON
,W/Uploader( 1638): No account for auth token provided
,I/qtaguid ( 1638): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1638, getuid(): 10012
,W/Uploader( 1638):  no longer exists, so no auth token.
,I/qtaguid ( 1638): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1638, getuid(): 10012
,E/SQLiteLog( 1638): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/art     ( 6703): WaitForGcToComplete blocked for 14.350ms for cause HomogeneousSpaceCompact,
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,V/AlarmManager(  874): waitForAlarm result :4
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7502): Starting books sync, d
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1638): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7502): Authentication error
E/BooksAccountManager( 7502): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7502): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7502): null auth token
,I/qtaguid ( 7502): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7502, getuid(): 10082
,I/qtaguid ( 7502): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7502, getuid(): 10082
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/qtaguid ( 7502): Untagging socket 34
,W/ApiaryClient( 7502): Error response from books API: {
W/ApiaryClient( 7502):  "error": {
W/ApiaryClient( 7502):   "errors": [
W/ApiaryClient( 7502):    {
W/ApiaryClient( 7502):     "domain": "global",
W/ApiaryClient( 7502):     "reason": "required",
W/ApiaryClient( 7502):     "message": "Login Required",
W/ApiaryClient( 7502):     "locationType": "header",
W/ApiaryClient( 7502):     "location": "Authorization"
W/ApiaryClient( 7502):    }
W/ApiaryClient( 7502):   ],
W/ApiaryClient( 7502):   "code": 401,
W/ApiaryClient( 7502):   "message": "Login Required"
W/ApiaryClient( 7502):  }
W/ApiaryClient( 7502): }
,W/ApiaryClient( 7502): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7502): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7319537935378895685&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7502): Headers suppressed
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  874): SIOP:: AP = 300, PST = 331, CUR = 300
,I/PowerManagerService(  874): [PWL] Off : 50s ago
,I/PowerManagerService(  874): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  874): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  874): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=874, ws=WorkSource{10082}) (elapsedTime=546),
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 5
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7502): Authentication error
E/BooksAccountManager( 7502): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7502): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7502): null auth token
,I/qtaguid ( 7502): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7502, getuid(): 10082
,I/qtaguid ( 7502): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7502, getuid(): 10082
,I/qtaguid ( 7502): Untagging socket 34
,W/ApiaryClient( 7502): Error response from books API: {
W/ApiaryClient( 7502):  "error": {
W/ApiaryClient( 7502):   "errors": [
W/ApiaryClient( 7502):    {
W/ApiaryClient( 7502):     "domain": "global",
W/ApiaryClient( 7502):     "reason": "required",
W/ApiaryClient( 7502):     "message": "Login Required",
W/ApiaryClient( 7502):     "locationType": "header",
W/ApiaryClient( 7502):     "location": "Authorization"
W/ApiaryClient( 7502):    }
W/ApiaryClient( 7502):   ],
W/ApiaryClient( 7502):   "code": 401,
W/ApiaryClient( 7502):   "message": "Login Required"
W/ApiaryClient( 7502):  }
W/ApiaryClient( 7502): }
W/ApiaryClient( 7502): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7502): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7319537935378895685&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7502): Headers suppressed
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7502): Authentication error
E/BooksAccountManager( 7502): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7502): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7502): null auth token
,I/qtaguid ( 7502): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7502, getuid(): 10082
,I/qtaguid ( 7502): Untagging socket 34
,W/ApiaryClient( 7502): Error response from books API: {
W/ApiaryClient( 7502):  "error": {
W/ApiaryClient( 7502):   "errors": [
W/ApiaryClient( 7502):    {
W/ApiaryClient( 7502):     "domain": "global",
W/ApiaryClient( 7502):     "reason": "required",
W/ApiaryClient( 7502):     "message": "Login Required",
W/ApiaryClient( 7502):     "locationType": "header",
W/ApiaryClient( 7502):     "location": "Authorization"
W/ApiaryClient( 7502):    }
W/ApiaryClient( 7502):   ],
W/ApiaryClient( 7502):   "code": 401,
W/ApiaryClient( 7502):   "message": "Login Required"
W/ApiaryClient( 7502):  }
W/ApiaryClient( 7502): }
,W/ApiaryClient( 7502): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7502): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7319537935378895685&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7502): Headers suppressed
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/BatteryService(  874): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/BooksSync( 7502): Soft error
E/BooksSync( 7502): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7502): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7319537935378895685&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7502): Headers suppressed
E/BooksSync( 7502): 
E/BooksSync( 7502): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7502): Sync error
E/BooksSync( 7502): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7502): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7319537935378895685&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7502): Headers suppressed
E/BooksSync( 7502): 
E/BooksSync( 7502): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7502): Finished books sync
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  874): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 158175, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  874): mCursor = null
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,E/HttpOperation( 6672): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6672): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6672): 	at kfv.a(PG:65)
E/HttpOperation( 6672): 	at kff.u(PG:385)
E/HttpOperation( 6672): 	at kfb.a(PG:29)
E/HttpOperation( 6672): 	at kff.l(PG:132)
E/HttpOperation( 6672): 	at dsf.a(PG:807)
E/HttpOperation( 6672): 	at fhk.a(PG:1126)
E/HttpOperation( 6672): 	at fhk.a(PG:908)
E/HttpOperation( 6672): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6672): 	at ihi.a(PG:22)
E/HttpOperation( 6672): 	at kft.a(PG:91)
E/HttpOperation( 6672): 	at kfv.a(PG:62)
E/HttpOperation( 6672): 	... 8 more
E/HttpOperation( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6672): 	at gde.c(Unknown Source)
E/HttpOperation( 6672): 	at gde.b(Unknown Source)
E/HttpOperation( 6672): 	at ihi.a(PG:19)
E/HttpOperation( 6672): 	... 10 more
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6672): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6672): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6672): 	at kfv.a(PG:65)
E/HttpOperation( 6672): 	at kff.u(PG:385)
E/HttpOperation( 6672): 	at kfb.a(PG:29)
E/HttpOperation( 6672): 	at kff.l(PG:132)
E/HttpOperation( 6672): 	at ieo.a(PG:43)
E/HttpOperation( 6672): 	at iep.a(PG:93)
E/HttpOperation( 6672): 	at fhn.a(PG:59)
E/HttpOperation( 6672): 	at lex.a(PG:85)
E/HttpOperation( 6672): 	at lex.b(PG:132)
E/HttpOperation( 6672): 	at fhk.a(PG:1146)
E/HttpOperation( 6672): 	at fhk.a(PG:908)
E/HttpOperation( 6672): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6672): 	at ihi.a(PG:22)
E/HttpOperation( 6672): 	at kft.a(PG:91)
E/HttpOperation( 6672): 	at kfv.a(PG:62)
E/HttpOperation( 6672): 	... 12 more
E/HttpOperation( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6672): 	at gde.c(Unknown Source)
E/HttpOperation( 6672): 	at gde.b(Unknown Source)
E/HttpOperation( 6672): 	at ihi.a(PG:19)
E/HttpOperation( 6672): 	... 14 more
E/ExperimentLoader( 6672): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6672): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6672): 	at kfv.a(PG:65)
E/ExperimentLoader( 6672): 	at kff.u(PG:385)
E/ExperimentLoader( 6672): 	at kfb.a(PG:29)
E/ExperimentLoader( 6672): 	at kff.l(PG:132)
E/ExperimentLoader( 6672): 	at ieo.a(PG:43)
E/ExperimentLoader( 6672): 	at iep.a(PG:93)
E/ExperimentLoader( 6672): 	at fhn.a(PG:59)
E/ExperimentLoader( 6672): 	at lex.a(PG:85)
E/ExperimentLoader( 6672): 	at lex.b(PG:132)
E/ExperimentLoader( 6672): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6672): 	at fhk.a(PG:908)
E/ExperimentLoader( 6672): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6672): 	at ihi.a(PG:22)
E/ExperimentLoader( 6672): 	at kft.a(PG:91)
E/ExperimentLoader( 6672): 	at kfv.a(PG:62)
E/ExperimentLoader( 6672): 	... 12 more
E/ExperimentLoader( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6672): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6672): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6672): 	at ihi.a(PG:19)
E/ExperimentLoader( 6672): 	... 14 more
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6672): [getaccountstatus] Unexpected exception
E/HttpOperation( 6672): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6672): 	at kfv.a(PG:65)
E/HttpOperation( 6672): 	at kff.u(PG:385)
E/HttpOperation( 6672): 	at kfb.a(PG:29)
E/HttpOperation( 6672): 	at ixd.a(PG:248)
E/HttpOperation( 6672): 	at ixd.b(PG:206)
E/HttpOperation( 6672): 	at ixd.a(PG:175)
E/HttpOperation( 6672): 	at fig.a(PG:78)
E/HttpOperation( 6672): 	at lex.a(PG:85)
E/HttpOperation( 6672): 	at lex.b(PG:132)
E/HttpOperation( 6672): 	at fhk.a(PG:1146)
E/HttpOperation( 6672): 	at fhk.a(PG:908)
E/HttpOperation( 6672): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6672): 	at ihi.a(PG:22)
E/HttpOperation( 6672): 	at kft.a(PG:91)
E/HttpOperation( 6672): 	at kfv.a(PG:62)
E/HttpOperation( 6672): 	... 12 more
E/HttpOperation( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6672): 	at gde.c(Unknown Source)
E/HttpOperation( 6672): 	at gde.b(Unknown Source)
E/HttpOperation( 6672): 	at ihi.a(PG:19)
E/HttpOperation( 6672): 	... 14 more
,E/EsSyncAdapterService( 6672): Sync failure
E/EsSyncAdapterService( 6672): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6672): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6672): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6672): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6672): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6672): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6672): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6672): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6672): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6672): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6672): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6672): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6672): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6672): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6672): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6672): 	... 10 more
E/EsSyncAdapterService( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6672): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6672): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6672): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6672): 	... 12 more
E/EsSyncAdapterService( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6672): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6672): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6672): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6672): 	... 14 more
,I/PhoneStatusBar( 1173): Icon Only
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,D/PanelView( 1173): There is/are notification(s) 
,E/SQLiteLog( 1638): (10) POSIX Error : 11 SQLite Error : 3850
,D/PanelView( 1173): There is/are notification(s) 
,D/SyncManager(  874): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 187448, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  874): mCursor = null
,I/art     (  874): Explicit concurrent mark sweep GC freed 38305(2039KB) AllocSpace objects, 19(759KB) LOS objects, 30% free, 36MB/52MB, paused 1.905ms total 166.202ms
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/Watchdog(  874): !@Sync 6
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  874): SIOP:: AP = 300, PST = 325, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/BatteryService(  874): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 313, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  874): [PWL] Off : 75s ago
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  330): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  330): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  282): DCD ON
,V/AlarmManager(  874): waitForAlarm result :4
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/BatteryService(  874): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 307, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,E/Watchdog(  874): !@Sync 7
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 303, CUR = 300
,V/AlarmManager(  874): waitForAlarm result :8
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/BatteryService(  874): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  282): DCD ON
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 300, CUR = 300
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  874): [PWL] Off : 105s ago
,E/SMD     (  282): DCD ON
,V/AlarmManager(  874): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  874): stay LED for fully charged
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
I/MotionRecognitionService(  874): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7502): Starting books sync, d
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1638): Explicit concurrent mark sweep GC freed 49577(2MB) AllocSpace objects, 67(4MB) LOS objects, 39% free, 18MB/30MB, paused 1.474ms total 79.965ms
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1638): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7502): Authentication error
E/BooksAccountManager( 7502): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7502): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7502): null auth token
,I/qtaguid ( 7502): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7502, getuid(): 10082
,I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 7502): Untagging socket 34
,W/ApiaryClient( 7502): Error response from books API: {
W/ApiaryClient( 7502):  "error": {
W/ApiaryClient( 7502):   "errors": [
W/ApiaryClient( 7502):    {
W/ApiaryClient( 7502):     "domain": "global",
W/ApiaryClient( 7502):     "reason": "required",
W/ApiaryClient( 7502):     "message": "Login Required",
W/ApiaryClient( 7502):     "locationType": "header",
W/ApiaryClient( 7502):     "location": "Authorization"
W/ApiaryClient( 7502):    }
W/ApiaryClient( 7502):   ],
W/ApiaryClient( 7502):   "code": 401,
W/ApiaryClient( 7502):   "message": "Login Required"
W/ApiaryClient( 7502):  }
W/ApiaryClient( 7502): }
,W/ApiaryClient( 7502): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7502): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-323399305596063369&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7502): Headers suppressed
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 297, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7502): Authentication error
E/BooksAccountManager( 7502): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7502): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7502): null auth token
,I/qtaguid ( 7502): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7502, getuid(): 10082
,I/qtaguid ( 7502): Untagging socket 34
,W/ApiaryClient( 7502): Error response from books API: {
W/ApiaryClient( 7502):  "error": {
W/ApiaryClient( 7502):   "errors": [
W/ApiaryClient( 7502):    {
W/ApiaryClient( 7502):     "domain": "global",
W/ApiaryClient( 7502):     "reason": "required",
W/ApiaryClient( 7502):     "message": "Login Required",
W/ApiaryClient( 7502):     "locationType": "header",
W/ApiaryClient( 7502):     "location": "Authorization"
W/ApiaryClient( 7502):    }
W/ApiaryClient( 7502):   ],
W/ApiaryClient( 7502):   "code": 401,
W/ApiaryClient( 7502):   "message": "Login Required"
W/ApiaryClient( 7502):  }
W/ApiaryClient( 7502): }
,W/ApiaryClient( 7502): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7502): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-323399305596063369&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7502): Headers suppressed
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7502): Authentication error
E/BooksAccountManager( 7502): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7502): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7502): null auth token
,I/qtaguid ( 7502): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7502, getuid(): 10082
,I/qtaguid ( 7502): Untagging socket 34
,W/ApiaryClient( 7502): Error response from books API: {
W/ApiaryClient( 7502):  "error": {
W/ApiaryClient( 7502):   "errors": [
W/ApiaryClient( 7502):    {
W/ApiaryClient( 7502):     "domain": "global",
W/ApiaryClient( 7502):     "reason": "required",
W/ApiaryClient( 7502):     "message": "Login Required",
W/ApiaryClient( 7502):     "locationType": "header",
W/ApiaryClient( 7502):     "location": "Authorization"
W/ApiaryClient( 7502):    }
W/ApiaryClient( 7502):   ],
W/ApiaryClient( 7502):   "code": 401,
W/ApiaryClient( 7502):   "message": "Login Required"
W/ApiaryClient( 7502):  }
W/ApiaryClient( 7502): }
,W/ApiaryClient( 7502): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7502): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-323399305596063369&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7502): Headers suppressed
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,E/BooksSync( 7502): Soft error
E/BooksSync( 7502): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7502): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-323399305596063369&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7502): Headers suppressed
E/BooksSync( 7502): 
E/BooksSync( 7502): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7502): Sync error
E/BooksSync( 7502): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7502): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-323399305596063369&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7502): Headers suppressed
E/BooksSync( 7502): 
E/BooksSync( 7502): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7502): Finished books sync
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  874): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 223053, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  874): mCursor = null
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  282): DCD ON
,E/Watchdog(  874): !@Sync 8
,E/SMD     (  282): DCD ON
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/BatteryService(  874): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,D/BatteryService(  874): stay LED for fully charged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 293, CUR = 300
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  282): DCD ON
,V/AlarmManager(  874): waitForAlarm result :4
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/BatteryService(  874): stay LED for fully charged
,I/PowerManagerService(  874): [PWL] Off : 140s ago
,I/PowerManagerService(  874): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  874): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  874): [PWL]       PARTIAL_WAKE_LOCK              'SyncManagerHandleSyncAlarm' (uid=1000, pid=874, ws=null) (elapsedTime=88)
I/PowerManagerService(  874): [PWL]       PARTIAL_WAKE_LOCK              'SyncLoopWakeLock' (uid=1000, pid=874, ws=null) (elapsedTime=64)
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 1638): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
,D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,E/HttpOperation( 6672): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6672): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6672): 	at kfv.a(PG:65)
E/HttpOperation( 6672): 	at kff.u(PG:385)
E/HttpOperation( 6672): 	at kfb.a(PG:29)
E/HttpOperation( 6672): 	at kff.l(PG:132)
E/HttpOperation( 6672): 	at dsf.a(PG:807)
E/HttpOperation( 6672): 	at fhk.a(PG:1126)
E/HttpOperation( 6672): 	at fhk.a(PG:908)
E/HttpOperation( 6672): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6672): 	at ihi.a(PG:22)
E/HttpOperation( 6672): 	at kft.a(PG:91)
E/HttpOperation( 6672): 	at kfv.a(PG:62)
E/HttpOperation( 6672): 	... 8 more
E/HttpOperation( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6672): 	at gde.c(Unknown Source)
E/HttpOperation( 6672): 	at gde.b(Unknown Source)
E/HttpOperation( 6672): 	at ihi.a(PG:19)
E/HttpOperation( 6672): 	... 10 more
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 292, CUR = 300
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6672): [getaccountstatus] Unexpected exception
E/HttpOperation( 6672): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6672): 	at kfv.a(PG:65)
E/HttpOperation( 6672): 	at kff.u(PG:385)
E/HttpOperation( 6672): 	at kfb.a(PG:29)
E/HttpOperation( 6672): 	at ixd.a(PG:248)
E/HttpOperation( 6672): 	at ixd.b(PG:206)
E/HttpOperation( 6672): 	at ixd.a(PG:175)
E/HttpOperation( 6672): 	at fig.a(PG:78)
E/HttpOperation( 6672): 	at lex.a(PG:85)
E/HttpOperation( 6672): 	at lex.b(PG:132)
E/HttpOperation( 6672): 	at fhk.a(PG:1146)
E/HttpOperation( 6672): 	at fhk.a(PG:908)
E/HttpOperation( 6672): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6672): 	at ihi.a(PG:22)
E/HttpOperation( 6672): 	at kft.a(PG:91)
E/HttpOperation( 6672): 	at kfv.a(PG:62)
E/HttpOperation( 6672): 	... 12 more
E/HttpOperation( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6672): 	at gde.c(Unknown Source)
E/HttpOperation( 6672): 	at gde.b(Unknown Source)
E/HttpOperation( 6672): 	at ihi.a(PG:19)
E/HttpOperation( 6672): 	... 14 more
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/EsSyncAdapterService( 6672): Sync failure
E/EsSyncAdapterService( 6672): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6672): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6672): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6672): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6672): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6672): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6672): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6672): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6672): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6672): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6672): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6672): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6672): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6672): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6672): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6672): 	... 10 more
E/EsSyncAdapterService( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6672): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6672): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6672): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6672): 	... 12 more
E/EsSyncAdapterService( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6672): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6672): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6672): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6672): 	... 14 more
D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  874): mCursor = null
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6672): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6672): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6672): 	at kfv.a(PG:65)
E/HttpOperation( 6672): 	at kff.u(PG:385)
E/HttpOperation( 6672): 	at kfb.a(PG:29)
E/HttpOperation( 6672): 	at kff.l(PG:132)
E/HttpOperation( 6672): 	at dsf.a(PG:807)
E/HttpOperation( 6672): 	at fhk.a(PG:1126)
E/HttpOperation( 6672): 	at fhk.a(PG:908)
E/HttpOperation( 6672): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6672): 	at ihi.a(PG:22)
E/HttpOperation( 6672): 	at kft.a(PG:91)
E/HttpOperation( 6672): 	at kfv.a(PG:62)
E/HttpOperation( 6672): 	... 8 more
E/HttpOperation( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6672): 	at gde.c(Unknown Source)
E/HttpOperation( 6672): 	at gde.b(Unknown Source)
E/HttpOperation( 6672): 	at ihi.a(PG:19)
E/HttpOperation( 6672): 	... 10 more
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): There is/are notification(s) 
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
,D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SQLiteLog( 1638): (10) POSIX Error : 11 SQLite Error : 3850
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6672): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6672): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6672): 	at kfv.a(PG:65)
E/HttpOperation( 6672): 	at kff.u(PG:385)
E/HttpOperation( 6672): 	at kfb.a(PG:29)
E/HttpOperation( 6672): 	at kff.l(PG:132)
E/HttpOperation( 6672): 	at ieo.a(PG:43)
E/HttpOperation( 6672): 	at iep.a(PG:93)
E/HttpOperation( 6672): 	at fhn.a(PG:59)
E/HttpOperation( 6672): 	at lex.a(PG:85)
E/HttpOperation( 6672): 	at lex.b(PG:132)
E/HttpOperation( 6672): 	at fhk.a(PG:1146)
E/HttpOperation( 6672): 	at fhk.a(PG:908)
E/HttpOperation( 6672): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6672): 	at ihi.a(PG:22)
E/HttpOperation( 6672): 	at kft.a(PG:91)
E/HttpOperation( 6672): 	at kfv.a(PG:62)
E/HttpOperation( 6672): 	... 12 more
E/HttpOperation( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6672): 	at gde.c(Unknown Source)
E/HttpOperation( 6672): 	at gde.b(Unknown Source)
E/HttpOperation( 6672): 	at ihi.a(PG:19)
E/HttpOperation( 6672): 	... 14 more
,E/ExperimentLoader( 6672): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6672): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6672): 	at kfv.a(PG:65)
E/ExperimentLoader( 6672): 	at kff.u(PG:385)
E/ExperimentLoader( 6672): 	at kfb.a(PG:29)
E/ExperimentLoader( 6672): 	at kff.l(PG:132)
E/ExperimentLoader( 6672): 	at ieo.a(PG:43)
E/ExperimentLoader( 6672): 	at iep.a(PG:93)
E/ExperimentLoader( 6672): 	at fhn.a(PG:59)
E/ExperimentLoader( 6672): 	at lex.a(PG:85)
E/ExperimentLoader( 6672): 	at lex.b(PG:132)
E/ExperimentLoader( 6672): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6672): 	at fhk.a(PG:908)
E/ExperimentLoader( 6672): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6672): 	at ihi.a(PG:22)
E/ExperimentLoader( 6672): 	at kft.a(PG:91)
E/ExperimentLoader( 6672): 	at kfv.a(PG:62)
E/ExperimentLoader( 6672): 	... 12 more
E/ExperimentLoader( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6672): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6672): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6672): 	at ihi.a(PG:19)
E/ExperimentLoader( 6672): 	... 14 more
,I/PhoneStatusBar( 1173): Icon Only
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  874): uri = 14 selection = getSealedState
D/SecContentProvider2(  874): mCursor = null
D/SecContentProvider2(  874): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  874): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  874): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1173): Icon Only
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): There is/are notification(s) 
,E/HttpOperation( 6672): [getaccountstatus] Unexpected exception
E/HttpOperation( 6672): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6672): 	at kfv.a(PG:65)
E/HttpOperation( 6672): 	at kff.u(PG:385)
E/HttpOperation( 6672): 	at kfb.a(PG:29)
E/HttpOperation( 6672): 	at ixd.a(PG:248)
E/HttpOperation( 6672): 	at ixd.b(PG:206)
E/HttpOperation( 6672): 	at ixd.a(PG:175)
E/HttpOperation( 6672): 	at fig.a(PG:78)
E/HttpOperation( 6672): 	at lex.a(PG:85)
E/HttpOperation( 6672): 	at lex.b(PG:132)
E/HttpOperation( 6672): 	at fhk.a(PG:1146)
E/HttpOperation( 6672): 	at fhk.a(PG:908)
E/HttpOperation( 6672): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6672): 	at ihi.a(PG:22)
E/HttpOperation( 6672): 	at kft.a(PG:91)
E/HttpOperation( 6672): 	at kfv.a(PG:62)
E/HttpOperation( 6672): 	... 12 more
E/HttpOperation( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6672): 	at gde.c(Unknown Source)
E/HttpOperation( 6672): 	at gde.b(Unknown Source)
E/HttpOperation( 6672): 	at ihi.a(PG:19)
E/HttpOperation( 6672): 	... 14 more
,E/EsSyncAdapterService( 6672): Sync failure
E/EsSyncAdapterService( 6672): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6672): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6672): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6672): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6672): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6672): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6672): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6672): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6672): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6672): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6672): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6672): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6672): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6672): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6672): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6672): 	... 10 more
E/EsSyncAdapterService( 6672): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6672): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6672): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6672): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6672): 	... 12 more
E/EsSyncAdapterService( 6672): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6672): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6672): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6672): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6672): 	... 14 more
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  874): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 191103, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  874): mCursor = null
,E/SQLiteLog( 1638): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  874): !@Sync 9
,E/SMD     (  282): DCD ON
,V/AlarmManager(  874): waitForAlarm result :8
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 290, CUR = 300
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  874): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  874): stay LED for fully charged
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  874): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
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
,D/QSEECOMAPI: (  874): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  874): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  874): Trustlet response is completed
,W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/Watchdog(  874): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  874): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  874): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  874): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  874): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  874): [PWL] Off : 180s ago
,D/BatteryService(  874): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  874): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  874): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  874):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  874): Plugged
,D/BatteryService(  874): stay LED for fully charged
,I/MotionRecognitionService(  874): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1173):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3230): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3230): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  874): SIOP:: AP = 290, PST = 290, CUR = 300
,I/jxcore-log( 7586): --= Surplus to requirements =--
I/jxcore-log( 7586): 
,I/jxcore-log( 7586): ****TEST TOOK:  ms ****
I/jxcore-log( 7586): 
I/jxcore-log( 7586): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7586): 
,D/AndroidRuntime( 8447): 
D/AndroidRuntime( 8447): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8447): CheckJNI is OFF
,D/AndroidRuntime( 8447): setted country_code = Germany
D/AndroidRuntime( 8447): setted countryiso_code = DE
,D/AndroidRuntime( 8447): setted sales_code = DBT
D/AndroidRuntime( 8447): readGMSProperty: start
,D/AndroidRuntime( 8447): readGMSProperty: already setted!!
D/AndroidRuntime( 8447): readGMSProperty: end
D/AndroidRuntime( 8447): addProductProperty: start
,E/AffinityControl( 8447): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8447): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  874): START PACKAGE DELETE: observer{298421758}
D/PackageManager(  874): pkg{<packageName>}
D/PackageManager(  874): user{0}
D/PackageManager(  874): caller{2000}
D/PackageManager(  874): flags{3}
,D/PersonaManagerService(  874): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  874): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  874): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  874): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  874): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  874): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  874): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  874): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  874): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  874): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  874): !@killApplicatoin: 10367, uninstall pkg
,I/ActivityManager(  874): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
,I/ActivityManager(  874): Killing 7586:com.test.thalitest/u0a367 (adj 0): stop com.test.thalitest
,I/ActivityManager(  874):   Force finishing activity ActivityRecord{259015d3 u0 com.test.thalitest/.MainActivity t11}
,D/FocusedStackFrame(  874): Set to : 0
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/WifiService(  874): Client connection lost with reason: 4
,W/PackageSettings(  874): Skipping PackageSetting{b13d19d com.example.hello/10375} due to missing metadata
,I/ActivityManager(  874): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
,D/ConnectivityService(  874): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/art     ( 1556): Explicit concurrent mark sweep GC freed 11108(696KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/27MB, paused 426us total 19.067ms
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 4458): Explicit concurrent mark sweep GC freed 4026(225KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 14MB/24MB, paused 493us total 44.839ms
,D/ResourcesManager( 1462): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,I/InputReader(  874): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,W/ResourcesManager( 1462): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1462): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1462): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
W/GeofencerStateMachine( 2225): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.4.503: ( 7797): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager( 1462): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1462): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1462): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/SamsungIME( 1862): mOCRHelper is null
,I/KLMS-2.4.503: ( 7797): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1452283892347
I/KLMS-2.4.503: ( 7797): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.503: ( 7797): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/art     (  874): Explicit concurrent mark sweep GC freed 58432(3MB) AllocSpace objects, 56(1416KB) LOS objects, 30% free, 36MB/52MB, paused 1.985ms total 177.648ms
,I/art     (  874): WaitForGcToComplete blocked for 111.108ms for cause Explicit
D/ResourcesManager(  874): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 2847): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/RegisteredServicesCache( 1449): empty dynamic service
,D/SecContentProvider2(  874): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  874): mCursor = null
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  874): creating new AssetManager and set to /system/app/talkback/talkback.apk
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8479): MountEmulatedStorage()
I/libpersona( 8479): KNOX_SDCARD checking this for 10104
E/Zygote  ( 8479): v2
I/libpersona( 8479): KNOX_SDCARD not a persona
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/ActivityManager(  874): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8479 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/SELinux ( 8479): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8479): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8479): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/EnterpriseDeviceManagerService(  874): Package has changed for user 0
D/EnterpriseDeviceManagerService(  874): Admin package name: com.google.android.gms
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/TimaKeyStoreProvider( 8479): TimaSignature is unavailable
,D/ActivityThread( 8479): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,I/art     (  874): Explicit concurrent mark sweep GC freed 6856(345KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 5.109ms total 153.861ms
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 8479): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/SurfaceWidgetView( 1462): destroyHardwareResources():437003284
,V/WindowOrientationListener(  874): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  874): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  874): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  874): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  874): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/Launcher( 1462): onRestart, Launcher: 394356499
,D/Launcher( 1462): onStart, Launcher: 394356499
D/Launcher.HomeView( 1462): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2188): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2188): [237392/6] SurfaceWidget drawing first frame
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/elm:14451( 8479): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8479): ELMEngine.ELMEngine( context ).
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Books/Books.apk
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/StatusBarManagerService(  874): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/StatusBarManagerService(  874): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/elm:14451( 8479): MDMBridge.setEnterpriseBridge()
,D/elm:14451( 8479): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,E/Zygote  ( 8497): MountEmulatedStorage()
E/Zygote  ( 8497): v2
I/libpersona( 8497): KNOX_SDCARD checking this for 10017
I/libpersona( 8497): KNOX_SDCARD not a persona
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/ActivityManager(  874): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8497 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,D/elm:14451( 8479): ElmAgentService : onCreate()
,D/elm:14451( 8479): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/ResourcesManager(  874): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/elm:14451( 8479): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8479): MDMBridge.getInstance()
D/elm:14451( 8479): MDMBridge.getAllLicenseInfoFromSDK()
,D/PackageManager(  874): delete codoeFile: 
,D/PackageManager(  874): result of delete: 1{298421758}
,I/SELinux ( 8497): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8497): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8497): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/InputMethodManagerService(  874): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/elm:14451( 8479): MDMBridge.getAllLicenseInfoFromSDK()
,D/AndroidRuntime( 8447): Shutting down VM
W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService(  874): Got RemoteException sending setActive(false) notification to pid 7586 uid 10367
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/TimaKeyStoreProvider( 8497): TimaSignature is unavailable
,D/ActivityThread( 8497): Added TimaKeyStore provider
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/elm:14451( 8479): ElmAgentService : onDestroy().
W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/ActivityManager(  874): Killing 7138:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 8497): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1173): value : false
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/Timeline(  874): Timeline: Activity_windows_visible id: ActivityRecord{a111960 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:320062
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
D/ResourcesManager(  874): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/LockPatternUtilsCache( 1173): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1173): value : false
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8497): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8497): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8497): onReceive() : package name is not s health. Return !!!
,D/ResourcesManager(  874): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/PCWCLIENTTRACE_PushUtil( 7718): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7718): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7718): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7718): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  874): failed to open /acct/uid_10166/pid_7138/cgroup.procs: No such file or directory
,D/RCPManagerService(  874): PackageReceiver onReceive()
I/HarmonyEASService(  874): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  874): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,E/Zygote  ( 8515): MountEmulatedStorage()
E/Zygote  ( 8515): v2
I/libpersona( 8515): KNOX_SDCARD checking this for 10034
I/libpersona( 8515): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8515 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 6747:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,D/BackupManagerService(  874): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  874): Receieved: android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(  874): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,V/EnterpriseBillingPolicy(  874): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  874): uID is 10367
V/EnterpriseBillingPolicy(  874): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  874): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  874): getProfileForApplication - exit null
,V/EnterpriseBillingPolicy(  874): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  874): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  874): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  874): getBillingProfileForVpnEngine - end - null
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 8515): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 8515): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8515): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/TaskPersister(  874): removeObsoleteFile: deleting file=11_task.xml
,D/TaskPersister(  874): removeObsoleteFile: deleting file=11_task_thumbnail.png
,D/TimaKeyStoreProvider( 8515): TimaSignature is unavailable
,D/ActivityThread( 8515): Added TimaKeyStore provider
,W/Resources(  874): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  874): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager( 8515): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/libprocessgroup(  874): failed to open /acct/uid_10012/pid_6747/cgroup.procs: No such file or directory
,I/FeatureConfig( 8515): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/ResourcesManager(  874): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  874): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
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
,D/UsbSettingsManager(  874): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  874): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 8515): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8515): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8515): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8515): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8515): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8515): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8515): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8515): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8515): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8515): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8515): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8515): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8515): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8515): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8515): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8515): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8515): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8515): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8515): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8515): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8515): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8515): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8515): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8515): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8515): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8515): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8515): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8515): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8515): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8515): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8515): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8515): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8515): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8515): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/EventHub(  874): Removing device '/dev/input/event4' due to inotify event
,D/ResourcesManager( 8515): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8515): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8515): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8515): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8515): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8515): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8515): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8515): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8515): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8515): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 8515): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SharedPreferencesImpl( 8515): Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
,W/System.err( 8515): java.io.IOException: read failed: EIO (I/O error)
,F/libc    ( 8515): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7339a733 in tid 8515 (pp.galaxyfinder)
,I/EventHub(  874): Removing device '/dev/input/event5' due to inotify event
,E/audit_log( 2131): File locking failed. error= Bad file number
E/audit_log( 2131): File locking failed. error= Bad file number
,I/ActivityManager(  874): Process com.samsung.android.app.galaxyfinder (pid 8515)(adj 0) has died(204,503)
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  874): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8536 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,E/Zygote  ( 8536): MountEmulatedStorage()
E/Zygote  ( 8536): v2
I/libpersona( 8536): KNOX_SDCARD checking this for 10035
,I/libpersona( 8536): KNOX_SDCARD not a persona
,I/EventHub(  874): Removing device '/dev/input/event6' due to inotify event
,I/SELinux ( 8536): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
I/Zygote  (  323): Process 8515 exited due to signal (7)
,E/SELinux ( 8536): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/EventHub(  874): Removing device '/dev/input/event7' due to inotify event
,D/TimaKeyStoreProvider( 8536): TimaSignature is unavailable
,D/ActivityThread( 8536): Added TimaKeyStore provider
,D/ResourcesManager( 8536): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/ContextImpl( 8536): Unable to create files subdir /data/data/com.sec.android.app.shealth/cache
E/ActivityThread( 8536): Unable to setupGraphicsSupport due to missing cache directory
,W/        ( 8536): Zip: failed reading lfh name from offset 418254
,F/libc    ( 8536): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7429da62 in tid 8536 (oid.app.shealth)
,F/libc    ( 8536): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2131): File locking failed. error= Bad file number
,I/ActivityManager(  874): Process com.sec.android.app.shealth (pid 8536)(adj 0) has died(204,503)
,I/EventHub(  874): Removing device '/dev/input/event8' due to inotify event
,F/libc    ( 7861): Fatal signal 7 (SIGBUS), code 2, fault addr 0x781e4a00 in tid 7861 (om.sec.spp.push)
,F/libc    ( 7861): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2131): File locking failed. error= Bad file number
,I/ActivityManager(  874): Process com.sec.spp.push (pid 7861)(adj 0) has died(209,503)
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8555): MountEmulatedStorage()
E/Zygote  ( 8555): v2
I/libpersona( 8555): KNOX_SDCARD checking this for 10038
I/libpersona( 8555): KNOX_SDCARD not a persona
,I/EventHub(  874): Removing device '/dev/input/event9' due to inotify event
,I/ActivityManager(  874): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8555 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Zygote  (  323): Process 7861 exited due to signal (7)
I/Zygote  (  323): Process 8536 exited due to signal (7)
,I/SELinux ( 8555): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 8555): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/EventHub(  874): Removing device '/dev/input/event10' due to inotify event
,D/TimaKeyStoreProvider( 8555): TimaSignature is unavailable
,D/ActivityThread( 8555): Added TimaKeyStore provider
,D/ResourcesManager( 8555): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/ContextImpl( 8555): Unable to create files subdir /data/data/com.sec.spp.push/cache
E/ActivityThread( 8555): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8555): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb3af127d in tid 8555 (moteNotiProcess)
F/libc    ( 8555): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2131): File locking failed. error= Bad file number
,I/EventHub(  874): Removing device '/dev/input/event11' due to inotify event
,I/ActivityManager(  874): Process com.sec.spp.push:RemoteNotiProcess (pid 8555)(adj 0) has died(208,504)
,E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  874): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8571): MountEmulatedStorage()
,E/Zygote  ( 8571): v2
I/libpersona( 8571): KNOX_SDCARD checking this for 10042
I/libpersona( 8571): KNOX_SDCARD not a persona
,I/ActivityManager(  874): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8571 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 8571): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
I/Zygote  (  323): Process 8555 exited due to signal (7)
,E/SELinux ( 8571): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8571): TimaSignature is unavailable
,D/ActivityThread( 8571): Added TimaKeyStore provider
,D/ResourcesManager( 8571): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 8571): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8571): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ContextImpl( 8571): Unable to create files subdir /data/data/com.samsung.android.sdk.samsunglink/cache
,E/ActivityThread( 8571): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8571): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7429da62 in tid 8571 (sdk.samsunglink)
,F/libc    ( 8571): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2131): File locking failed. error= Bad file number
,I/ActivityManager(  874): Process com.samsung.android.sdk.samsunglink (pid 8571)(adj 0) has died(209,504)
,I/SA      ( 7894): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7894): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10367 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,F/libc    ( 1774): Fatal signal 7 (SIGBUS), code 2, fault addr 0x77e0044c in tid 1774 (d.process.acore)
,F/libc    ( 1774): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2131): File locking failed. error= Bad file number

```
