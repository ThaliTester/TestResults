#### Test 506502783fcf234_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
--------- beginning of system
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7428): null auth token
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
I/qtaguid ( 7428): Untagging socket 34
W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
W/ApiaryClient( 7428): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6854691893912595333&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
D/AndroidRuntime( 7485): 
D/AndroidRuntime( 7485): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7485): CheckJNI is OFF
D/AndroidRuntime( 7485): setted country_code = Germany
D/AndroidRuntime( 7485): setted countryiso_code = DE
D/AndroidRuntime( 7485): setted sales_code = DBT
D/AndroidRuntime( 7485): readGMSProperty: start
D/AndroidRuntime( 7485): readGMSProperty: already setted!!
D/AndroidRuntime( 7485): readGMSProperty: end
D/AndroidRuntime( 7485): addProductProperty: start
E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
E/AffinityControl( 7485): AffinityControl: registerfunction enter
D/AndroidRuntime( 7485): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  897): inState():  stateMachine is null !!
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  897): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  897): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  897): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 897  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  897): mDVFSHelper.acquire()
D/FocusedStackFrame(  897): Set to : 0
D/Launcher.HomeView( 1497): onPause
D/Launcher( 1497): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 7485): Shutting down VM
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
V/TaskCloserActivity( 7268): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/Zygote  ( 7507): MountEmulatedStorage()
E/Zygote  ( 7507): v2
I/libpersona( 7507): KNOX_SDCARD checking this for 10367
I/libpersona( 7507): KNOX_SDCARD not a persona
I/ActivityManager(  897): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7507 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
I/SELinux ( 7507): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SELinux ( 7507): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7507): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBarManagerService(  897): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/MicrophoneInputStream( 1575): mic_close gfk@3cb863a1
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/AudioPolicyManager(  290): stopInput() input 30
V/AudioPolicyManager(  290): releaseInput() 30
V/AudioPolicyManager(  290): closeInput(30)
I/HotwordRecognitionRnr( 1575): Stopping hotword detection.
I/HotwordRecognitionRnr( 1575): Hotword detection finished
V/audio_hw_primary(  290): in_standby: enter
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/TimaKeyStoreProvider( 7507): TimaSignature is unavailable
D/ActivityThread( 7507): Added TimaKeyStore provider
V/WindowOrientationListener(  897): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  897): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  897): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  897): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  897): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  897): Display changed displayId=0
D/Launcher.HomeView( 1497): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2164): [237392/6] Surface widget pause on instance = 1
D/accuweather( 2164): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2164): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2164): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2164): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SurfaceWidgetView( 1497): destroyHardwareResources():240378142
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBarManagerService(  897): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
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
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/audio_route(  290): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  290): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  290): stop_input_stream: exit: status(0)
V/audio_hw_primary(  290): in_standby: exit:  status(0)
V/audio_hw_primary(  290): adev_close_input_stream
V/audio_hw_primary(  290): in_standby: enter
V/audio_hw_primary(  290): in_standby: exit:  status(0)
E/audio_hw_primary(  290): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  290): releaseInput() exit
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2164): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2164): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/ResourcesManager( 7507): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
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
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/Launcher( 1497): onTrimMemory. Level: 20
D/PowerManagerService(  897): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1169 (0x0)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SurfaceWidgetView( 1497): destroyHardwareResources():240378142
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/WebViewFactory( 7507): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7507): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/LibraryLoader( 7507): Loading: webviewchromium
I/LibraryLoader( 7507): Time to load native libraries: 2 ms (timestamps 6518-6520)
I/LibraryLoader( 7507): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/WebViewChromiumFactoryProvider( 7507): Binding Chromium to main looper Looper (main, tid 1) {3bf7803c}
I/LibraryLoader( 7507): Expected native library version number "",actual native library version number ""
I/chromium( 7507): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7507): Initializing chromium process, renderers=0
W/art     ( 7507): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/chromium( 7507): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7507): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7507): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
E/BooksSync( 7428): Soft error
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6854691893912595333&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7428): Headers suppressed
E/BooksSync( 7428): 
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7428): Sync error
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6854691893912595333&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7428): Headers suppressed
E/BooksSync( 7428): 
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7428): Finished books sync
D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/Adreno-EGL( 7507): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7507): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7507): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7507): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7507): Remote Branch: 
I/Adreno-EGL( 7507): Local Patches: 
I/Adreno-EGL( 7507): Reconstruct Branch: 
D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 68428, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  897): Killing 6774:com.sec.pcw.device/1000 (adj 15): bgCount ##41
D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
W/chromium( 7507): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7507): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_6774/cgroup.procs: No such file or directory
D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  897): mCursor = null
W/art     ( 7507): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7507): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SystemWebViewEngine( 7507): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/art     ( 7507): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7507): Attempt to remove local handle scope entry from IRT, ignoring
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
D/Activity( 7507): performCreate Call secproduct feature valuefalse
D/Activity( 7507): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/OpenGLRenderer( 7507): Render dirty regions requested: true
D/ActivityManager(  897): post active user change for 0
D/KnoxTimeoutHandler(  897): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  897): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
I/OpenGLRenderer( 7507): Initialized EGL, version 1.4
D/LockPatternUtilsCache( 1169): value : false
I/OpenGLRenderer( 7507): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7507): Enabling debug mode 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/InputMethodManagerService(  897): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager(  897): Displayed com.test.thalitest/.MainActivity: +662ms
I/Timeline( 7507): Timeline: Activity_idle id: android.os.BinderProxy@3460251f time:96881
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
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/LockPatternUtilsCache( 1169): value : false
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/JsMessageQueue( 7507): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/chromium( 7507): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7507): 
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
D/jxcore_app_log( 7507): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259379584
D/JX-Cordova( 7507): jxcore cordova android initializing
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (7/8)
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (-2/8)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/CustomFrequencyManagerService(  897): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 897  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  897): mDVFSHelper.release()
I/Timeline(  897): Timeline: Activity_windows_visible id: ActivityRecord{100cbbd5 u0 com.test.thalitest/.MainActivity t11} time:97113
D/CustomFrequencyManagerService(  897): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 897  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/Adreno-ES20( 7507): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7507): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/GAV2    ( 7428): Thread[GAThread,5,main]: No campaign data found.
,D/SSRM:m  (  897): SIOP:: AP = 360, PST = 426, CUR = 300
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CustomFrequencyManagerService(  897): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 897  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,W/jxcore-log( 7507): Initializing JXcore engine
,W/jxcore-log( 7507): JXcore engine is ready
W/jxcore-log( 7507): Starting JXcore engine
,E/auditd  ( 2179): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  897): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  897): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7571): MountEmulatedStorage()
E/Zygote  ( 7571): v2
I/libpersona( 7571): KNOX_SDCARD checking this for 1000
I/libpersona( 7571): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7571 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7571): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7571): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7571): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/TimaKeyStoreProvider( 7571): TimaSignature is unavailable
,D/ActivityThread( 7571): Added TimaKeyStore provider
,W/jxcore-log( 7507): Platform android
W/jxcore-log( 7507): 
,W/jxcore-log( 7507): Process ARCH arm
W/jxcore-log( 7507): 
,D/ResourcesManager( 7571): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7571):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7571):  SeDenialReceiver : File path = null
,I/ActivityManager(  897): Killing 6524:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,W/libprocessgroup(  897): failed to open /acct/uid_10034/pid_6524/cgroup.procs: No such file or directory
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7507): JXcore Cordova bridge is ready!
I/jxcore-log( 7507): 
W/jxcore-log( 7507): JXcore engine is started
,I/Choreographer( 7507): Skipped 134 frames!  The application may be doing too much work on its main thread.
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  897): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
D/PowerManagerService(  897): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  897): lcd : 7 +
,D/lights  (  897): lcd : 7 -
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
D/lights  (  897): lcd : 1 +
,D/lights  (  897): lcd : 1 -
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/jxcore-log( 7507): Toggling radios to true
I/jxcore-log( 7507): 
,D/BluetoothAdapter( 7507): enable()
,D/BluetoothAdapter( 7507): enable(): BT is already enabled..!
,D/WifiService(  897): New client listening to asynchronous messages
,I/WifiManager( 7507): packageName : com.test.thalitest
,D/SecContentProvider(  897): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  897): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  897): mCursor = null
,D/WifiService(  897): setWifiEnabled: true pid=7507, uid=10367
,E/WifiService(  897): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  897): Permission Denial: getCurrentUser() from pid=7507, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  897): Failed getting userId using ActivityManagerNative
W/WifiService(  897): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7507, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  897): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  897): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  897): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  897): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  897): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  897): name = wifi_on
,I/WifiService(  897): disconnect: pid=7507, uid=10367
,I/jxcore-log( 7507): Radios toggled
I/jxcore-log( 7507): 
I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7507): Got Device Bluetooth address: B0:C5:59:3F:75:69
I/jxcore-log( 7507): 
,I/jxcore-log( 7507): Perf Test app loaded loaded
I/jxcore-log( 7507): 
,I/jxcore-log( 7507): check test folder
I/jxcore-log( 7507): 
,I/jxcore-log( 7507): found test : ./testFindPeers.js
I/jxcore-log( 7507): 
,I/wpa_supplicant( 1293): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1293): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1293): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  897): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1293): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1293): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1293): Disconnected - do not scan
I/wpa_supplicant( 1293): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  897): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  897): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  897): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  897): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  897): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  897): InactiveState{ what=143375 }
,D/WifiP2pService(  897): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/AlarmManager(  897): waitForAlarm result :4
,I/jxcore-log( 7507): found test : ./testSendData.js
I/jxcore-log( 7507): 
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1693): Read error: ssl=0xab5a1600: I/O error during system call, Connection timed out
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,V/NativeCrypto( 1693): SSL shutdown failed: ssl=0xab5a1600: I/O error during system call, Broken pipe
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/WifiStateMachine(  897): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  897): updateNetworkInfo()
,D/ConnectivityService(  897): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  897): updateNetworkInfo()
D/ConnectivityService(  897): ignoring duplicate network state non-change
,D/ConnectivityService(  897): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiConfigStore(  897): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller(  897): evaluateTrafficStatsPolling
,I/CLocInfoService(  897): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  897): ValidatedState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  897): DefaultState{ when=-4ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  897): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  897): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
E/SMD     (  285): DCD ON
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  897): Validated
,E/WifiStateMachine(  897): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1293): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1293): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1293): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1293): First Scan Start
,E/WifiStateMachine(  897): ConnectModeState: Network connection lost 
,I/wpa_supplicant( 1293): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  897): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  897): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/WifiP2pService(  897): InactiveState{ what=143375 }
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/WifiP2pService(  897): P2pEnabledState{ what=143375 }
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,D/ConnectivityService(  897): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  897): calling update connectivity
D/ConnectivityService(  897):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  897):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/EntConnectivity(  897): Not allowed due to - mEnabled false
D/ConnectivityService(  897): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/Nat464Xlat(  897): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  897): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  897): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  897): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService(  897): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  897): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  897): Disconnected - quitting
,D/CSLegacyTypeTracker(  897): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  897): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/TelephonyNetworkFactory( 1474): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiStateMachine(  897): updateConfiguredNetworkExpiration - currTime: 1450238244726
D/WifiStateMachine(  897): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/ConnectivityService(  897): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine(  897): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  897): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  897): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  897): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  897): NetworkAgent: NetworkAgent channel lost
,I/WifiTrafficPoller(  897): evaluateTrafficStatsPolling
,I/Hs20UtilService( 1300): Starting #6
,I/Hs20UtilService( 1300): Message received 5007
,I/CLocInfoService(  897): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  897): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  897): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,D/ConnectivityService(  897): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,E/WifiStateMachine(  897): setDetailed state send new extra info"NG700"
,D/SmartBondingService(  897): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  897): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  897): getSBEnabled() enabled =false
D/SmartBondingService(  897): getSBEnabled() enabled =false
D/SmartBondingService(  897): getSBEnabled() enabled =false
,D/SmartBondingService(  897): getNetworkEnabled : wifi : true mobile : true
,V/NetworkStats(  897): updateIfacesLocked()
D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
V/NetworkStats(  897): performPollLocked(flags=0x1)
D/NtpTrustedTime(  897): currentTimeMillis() cache hit
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ConnectivityService(  897): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
D/SecContentProvider2(  897): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  897): mCursor = null
I/NearbySettings( 1300): MountReceiver.onReceive - Set preference state off
,D/NetworkStatsFactory(  897): UpdateStatsForKnox
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
,D/NtpTrustedTime(  897): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
,V/NetworkStats(  897): performPollLocked() took 9ms
,D/NtpTrustedTime(  897): currentTimeMillis() cache hit
D/NtpTrustedTime(  897): currentTimeMillis() cache hit
D/NtpTrustedTime(  897): currentTimeMillis() cache hit
V/NetworkStats(  897): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  897): currentTimeMillis() cache hit
,D/SecContentProvider2(  897): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  897): mCursor = null
,V/NearbySettings( 1300): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/NtpTrustedTime(  897): currentTimeMillis() cache hit
D/NtpTrustedTime(  897): currentTimeMillis() cache hit
,I/Hs20UtilService( 1300): Starting #7
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Hs20UtilService( 1300): Message received 5007
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1300): MountReceiver.mPrefHandler - 7002
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/Choreographer( 7507): Skipped 78 frames!  The application may be doing too much work on its main thread.
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
I/chromium( 7507): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,I/chromium( 7507): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6659): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6659): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6659): [1] 5.onFinished: Scheduling replication attempt 2.
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  897): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  897): updateDataUsageMap
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2164): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/Tethering(  897): MasterInitialState.processMessage what=3
D/SmartBondingService(  897): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  897): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  897): getSBEnabled() enabled =false
D/SmartBondingService(  897): getSBEnabled() enabled =false
D/SmartBondingService(  897): getSBEnabled() enabled =false
I/CLocInfoService(  897): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  897): CLoinfo wifi false
,D/SmartBondingService(  897): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/SLocation(  897): No Active Data Connection
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5361): type=WIFI subType= reason=null isConnected=false
,I/SystemBroadcastReceiver( 7158): [#DCM#] [DCM_Performance] onReceive completed in time  2768 microsec. 
,I/SystemBroadcastReceiver( 7158): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7158): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7158): [#DCM#] setIsConnectedForExtractors 
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3795): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
E/Zygote  ( 7640): MountEmulatedStorage()
E/Zygote  ( 7640): v2
I/libpersona( 7640): KNOX_SDCARD checking this for 1000
I/libpersona( 7640): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7640 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7640): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3795): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/SELinux ( 7640): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7640): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7640): TimaSignature is unavailable
,D/ActivityThread( 7640): Added TimaKeyStore provider
,D/ResourcesManager( 7640): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 7640): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 7640): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7640): new DMDBOpenHelper instance
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/PCWCLIENTTRACE_PushUtil( 7640): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7640): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7640): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7640): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7640): noConnectivity : true
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7656): MountEmulatedStorage()
,E/Zygote  ( 7656): v2
I/libpersona( 7656): KNOX_SDCARD checking this for 10002
I/libpersona( 7656): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7656 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 4612:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,I/SELinux ( 7656): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7656): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7656): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7656): TimaSignature is unavailable
,D/ActivityThread( 7656): Added TimaKeyStore provider
,D/ResourcesManager( 7656): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,W/libprocessgroup(  897): failed to open /acct/uid_10035/pid_4612/cgroup.procs: No such file or directory
,I/ActivityManager(  897): Killing 6792:com.policydm/1000 (adj 15): bgCount ##41
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7678): MountEmulatedStorage()
,E/Zygote  ( 7678): v2
I/libpersona( 7678): KNOX_SDCARD checking this for 1000
I/libpersona( 7678): KNOX_SDCARD not a persona
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/ActivityManager(  897): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7678 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7678): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7678): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7678): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7678): TimaSignature is unavailable
,D/ActivityThread( 7678): Added TimaKeyStore provider
,W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_6792/cgroup.procs: No such file or directory
,D/ResourcesManager( 7678): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7678): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7678): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7678): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7678): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7678): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7678): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1293): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 1293): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1293): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1293): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  897): [1,450,238,245,790 ms] noteScanEnd no scan source
,E/WifiStateMachine(  897): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1a08bfcc sup_state=SCANNING debouncing=false
,E/Zygote  ( 7699): MountEmulatedStorage()
,E/Zygote  ( 7699): v2
I/libpersona( 7699): KNOX_SDCARD checking this for 10011
I/libpersona( 7699): KNOX_SDCARD not a persona
,I/SELinux ( 7699): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  897): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7699 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7699): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7699): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  897): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  897): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
I/CLocInfoService(  897): External Intent Received android.net.wifi.SCAN_RESULTS
E/WifiStateMachine(  897): setDetailed state send new extra info0x
,D/SecContentProvider2(  897): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  897): mCursor = null
,D/TimaKeyStoreProvider( 7699): TimaSignature is unavailable
,D/ActivityThread( 7699): Added TimaKeyStore provider
,D/ResourcesManager( 7699): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 1293): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1293): Associated with C0.AA.48
,E/WifiStateMachine(  897): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  897): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  897): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  897): mCursor = null
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/ActivityManager(  897): Killing 5119:com.sec.spp.push/u0a38 (adj 15): bgCount ##41
,I/wpa_supplicant( 1293): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/FOTA_Client( 7699): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
E/WifiStateMachine(  897): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  897): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  897): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  897): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  897): mCursor = null
,I/FOTA_Client( 7699): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/wpa_supplicant( 1293): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1293): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  897): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  897): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 1293): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1293): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1293): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1293): Blacklist: Clear (temp) 
,I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/SecContentProvider2(  897): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  897): mCursor = null
,E/WifiStateMachine(  897): Network connection established
,D/WifiNative-HAL(  897): callSECApiVoid - ID [50]
,E/WifiStateMachine(  897): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/CLocInfoService(  897): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  897): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  897): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  897): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  897): Got NetworkAgent Messenger
D/ConnectivityService(  897): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  897): updateNetworkInfo()
D/ConnectivityService(  897): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  897): NetworkAgent connected
E/WifiStateMachine(  897): L2ConnectedState "NG700" nid=0
,E/WifiConfigStore(  897): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  897): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  897): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  897): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  897): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  278): Setting iface cfg
,E/WifiStateMachine(  897): Start Dhcp Watchdog 2
,I/FOTA_Client( 7699): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  897): calculateWifiScore() report new score 60
,I/WifiStateMachine(  897): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  897): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
I/FOTA_Client( 7699): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,D/ConnectivityService(  897): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  897): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  897): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
I/FOTA_Client( 7699): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
E/WifiStateMachine(  897): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  897): failed to open /acct/uid_10038/pid_5119/cgroup.procs: No such file or directory
,E/Zygote  ( 7718): MountEmulatedStorage()
,E/Zygote  ( 7718): v2
I/libpersona( 7718): KNOX_SDCARD checking this for 10019
I/libpersona( 7718): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7718 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 6039:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/SELinux ( 7718): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7718): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7718): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  897): failed to open /acct/uid_10042/pid_6039/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7718): TimaSignature is unavailable
,D/ActivityThread( 7718): Added TimaKeyStore provider
,D/ResourcesManager( 7718): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,E/WifiStateMachine(  897): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  897): do suspend false
,D/SecContentProvider2(  897): uri = 20 selection = getPromptCredentialsEnabled
,D/WifiP2pService(  897): InactiveState{ what=143375 }
D/SecContentProvider2(  897): mCursor = null
D/WifiP2pService(  897): P2pEnabledState{ what=143375 }
,I/KLMS-2.4.503: ( 7718): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7718): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450238246054
,I/KLMS-2.4.503: ( 7718): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7718): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7718): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  897): Killing 6815:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7733): MountEmulatedStorage()
I/ActivityManager(  897): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7733 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 7733): v2
I/libpersona( 7733): KNOX_SDCARD checking this for 10037
I/libpersona( 7733): KNOX_SDCARD not a persona
,I/SELinux ( 7733): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7733): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7733): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  897): failed to open /acct/uid_10045/pid_6815/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7733): TimaSignature is unavailable
,D/ActivityThread( 7733): Added TimaKeyStore provider
,D/ResourcesManager( 7733): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7733): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7748): MountEmulatedStorage()
,E/Zygote  ( 7748): v2
I/libpersona( 7748): KNOX_SDCARD checking this for 1000
I/libpersona( 7748): KNOX_SDCARD not a persona
I/ActivityManager(  897): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7748 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 6836:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/art     (  316): Explicit concurrent mark sweep GC freed 8732(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 268us total 16.718ms
,I/SELinux ( 7748): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7748): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7748): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 8.201ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.819ms
,W/libprocessgroup(  897): failed to open /acct/uid_10051/pid_6836/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7748): TimaSignature is unavailable
,D/ActivityThread( 7748): Added TimaKeyStore provider
,D/ResourcesManager( 7748): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/dhcpcd  ( 7768): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7768): version 5.5.6 starting
,E/dhcpcd  ( 7768): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7780): MountEmulatedStorage()
,E/Zygote  ( 7780): v2
I/libpersona( 7780): KNOX_SDCARD checking this for 10038
I/libpersona( 7780): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7780 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 6858:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/dhcpcd  ( 7768): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7768): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7768): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7768): bssid match
,I/dhcpcd  ( 7768): wlan0: rebinding lease of 192.168.1.135
,I/SELinux ( 7780): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7780): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7780): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  897): failed to open /acct/uid_10058/pid_6858/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7780): TimaSignature is unavailable
,D/ActivityThread( 7780): Added TimaKeyStore provider
,D/ResourcesManager( 7780): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 7780): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7780): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7780): PushLog.txt file is not deleted.
,D/SPPClientService( 7780): PushLog.txt file is not deleted.
D/SPPClientService( 7780): ============PushLog. stop!
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/SPPClientService( 7780): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7797): MountEmulatedStorage()
E/Zygote  ( 7797): v2
I/libpersona( 7797): KNOX_SDCARD checking this for 10045
I/libpersona( 7797): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7797 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 6228:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SELinux ( 7797): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7797): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7797): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 7780): [[SystemStateMonitorService]] No Active Internet
,W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_6228/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7797): TimaSignature is unavailable
,D/ActivityThread( 7797): Added TimaKeyStore provider
,D/ResourcesManager( 7797): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/SA      ( 7797): [SSP] onCreated
,I/SA      ( 7797): [TPM] There is no property file
,I/SA      ( 7797): [SCU] isHaveSA() - false
,I/SA      ( 7797): [TPM] getModelProperty : null
,I/SA      ( 7797): [TPM] getCSCProperty : null
,I/SA      ( 7797): [DM] init START
,I/SA      ( 7797): [DM] This device is not a Vodafone
,W/ResourceType( 7797): Failure getting entry for 0x7f06000f (t=5 e=15) (error -75)
,W/ResourceType( 7797): Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
W/ResourceType( 7797): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 7797): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 7797): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7797): Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
,W/ResourceType( 7797): Failure getting entry for 0x7f060013 (t=5 e=19) (error -75)
,W/ResourceType( 7797): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7797): Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
W/ResourceType( 7797): Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,W/ResourceType( 7797): Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
W/ResourceType( 7797): Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
W/ResourceType( 7797): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 7797): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7797): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 7797): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 7797): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 7797): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 7797): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 7797): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,I/SA      ( 7797): [SCU] isHaveSA() - false
I/SA      ( 7797): support phone number id : false
,I/SA      ( 7797): [DM] init END
I/SA      ( 7797): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7797): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 7797): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7797): [SLFUCHKMGR] constructor called
,I/SA      ( 7797): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7797): [OR] == isSIMCardReady false ==
,I/SA      ( 7797): [SCU] == networkStateCheck == false
I/SA      ( 7797): [OR] onReceive END
,I/ActivityManager(  897): Killing 6592:com.sec.chaton/u0a86 (adj 15): bgCount ##41
,D/accuweather( 7337): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7337): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7337): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7337): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7337): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7337): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/daemonapp( 1335): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7337): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1335): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/libprocessgroup(  897): failed to open /acct/uid_10086/pid_6592/cgroup.procs: No such file or directory
,D/accuweather( 7337): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1335): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7337): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7337): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7821): MountEmulatedStorage()
,E/Zygote  ( 7821): v2
I/libpersona( 7821): KNOX_SDCARD checking this for 1000
I/libpersona( 7821): KNOX_SDCARD not a persona
I/ActivityManager(  897): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7821 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7821): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7821): TimaSignature is unavailable
,D/ActivityThread( 7821): Added TimaKeyStore provider
,D/ResourcesManager( 7821): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7821): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7821): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7821): premStatus:2
,I/KnoxUsageLogPro( 7821): isEulaShown : false
,I/KnoxUsageLogPro( 7821): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7836): MountEmulatedStorage()
E/Zygote  ( 7836): v2
I/libpersona( 7836): KNOX_SDCARD checking this for 10086
I/libpersona( 7836): KNOX_SDCARD not a persona
,I/SELinux ( 7836): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  897): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.NetStateReceiver: pid=7836 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7836): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7836): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager(  897): Killing 6879:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7836): TimaSignature is unavailable
,D/ActivityThread( 7836): Added TimaKeyStore provider
,D/ResourcesManager( 7836): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7836): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,W/libprocessgroup(  897): failed to open /acct/uid_10098/pid_6879/cgroup.procs: No such file or directory
,D/PushModule( 7836): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 7836): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 7836): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 7836): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 7836): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  897): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 7836): [1][a] ChatONV isn't installed.
,D/ChatON  ( 7836): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7855): MountEmulatedStorage()
,E/Zygote  ( 7855): v2
I/libpersona( 7855): KNOX_SDCARD checking this for 10088
I/libpersona( 7855): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7855 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  897): Killing 6932:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,I/SELinux ( 7855): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7855): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7855): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7855): TimaSignature is unavailable
,D/ActivityThread( 7855): Added TimaKeyStore provider
,D/ResourcesManager( 7855): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  897): failed to open /acct/uid_10033/pid_6932/cgroup.procs: No such file or directory
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/ActivityManager(  897): Killing 6910:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,D/Headlines( 5491): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5491): getCountryCode(): countryCode = DE
,D/Headlines( 5491): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5491): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5491): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5491): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5491): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5491): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5491): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7768): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,E/Zygote  ( 7871): MountEmulatedStorage()
E/Zygote  ( 7871): v2
I/libpersona( 7871): KNOX_SDCARD checking this for 10128
I/libpersona( 7871): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7871 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dhcpcd  ( 7768): wlan0: leased 192.168.1.135 for 86400 seconds,
,E/WifiStateMachine(  897): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  897): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  897): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/SELinux ( 7871): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7871): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7871): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7871): TimaSignature is unavailable
,D/ActivityThread( 7871): Added TimaKeyStore provider
,W/libprocessgroup(  897): failed to open /acct/uid_10099/pid_6910/cgroup.procs: No such file or directory
,D/ResourcesManager( 7871): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7871): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7871): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7871): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7871): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/WebViewFactory( 7871): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7871): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7871): Loading: webviewchromium
,I/LibraryLoader( 7871): Time to load native libraries: 4 ms (timestamps 3306-3310)
,I/LibraryLoader( 7871): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7871): Binding Chromium to main looper Looper (main, tid 1) {75b1dda}
,I/LibraryLoader( 7871): Expected native library version number "",actual native library version number ""
,I/chromium( 7871): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7871): Initializing chromium process, renderers=0
,W/art     ( 7871): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid( 7871): Requires BLUETOOTH permission
W/chromium( 7871): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7871): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7871): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/Adreno-EGL( 7871): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7871): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7871): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7871): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7871): Remote Branch: 
I/Adreno-EGL( 7871): Local Patches: 
I/Adreno-EGL( 7871): Reconstruct Branch: 
,E/WifiStateMachine(  897): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  897): InactiveState{ what=143375 }
,D/WifiP2pService(  897): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  897): WifiStateMachine DHCP successful
,E/WifiStateMachine(  897): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  897): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/ConnectivityService(  897): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  897): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  897): Not connected state, yet.
E/WifiStateMachine(  897): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  897): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  897): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  897): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
,D/WifiNative-HAL(  897): callSECApiInt - ID [210]
E/WifiStateMachine(  897): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  897): updateNetworkInfo()
,D/ConnectivityService(  897): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  897): Adding iface wlan0 to network 503
,I/CLocInfoService(  897): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  897): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  897): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  897): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  897): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  897): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  897): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  897): Now, connected state.
E/WifiStateMachine(  897): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/WifiTrafficPoller(  897): evaluateTrafficStatsPolling
,E/WifiStateMachine(  897): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/CLocInfoService(  897): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/WifiTrafficPoller(  897): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  897): mBoosterFLAG : 0
I/WifiTrafficPoller(  897): current booster mode : FullMode
,E/WifiStateMachine(  897): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiNative-HAL(  897): callSECApiVoid - ID [212]
,D/ConnectivityService(  897): Adding Route [fe80::/64 -> :: wlan0] to network 503
E/WifiStateMachine(  897): ConnectedState Enter  mScreenOn=true scanperiod=20000
,I/CLocInfoService(  897): External Intent Received android.net.wifi.STATE_CHANGE
D/ConnectivityService(  897): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  897): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  897): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  897): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  897): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  278): QcRouteController
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,I/WifiStateMachine(  897): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/NSApplication( 7871): Starting up...
,V/        (  278): QcRouteController
,V/        (  278): QcRouteController
,V/        (  278): QcRouteController
,V/        (  278): QcRouteController
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,V/        (  278): QcRouteController
,V/        (  278): QcRouteController
,E/Zygote  ( 7972): MountEmulatedStorage()
E/Zygote  ( 7972): v2
,I/libpersona( 7972): KNOX_SDCARD checking this for 10138
I/libpersona( 7972): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7972 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  897): Killing 6976:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,V/        (  278): QcRouteController
,E/WifiStateMachine(  897): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  897): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService(  897): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  897): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  897): getSBEnabled() enabled =false
D/SmartBondingService(  897): getSBEnabled() enabled =false
D/SmartBondingService(  897): getSBEnabled() enabled =false
,D/ConnectivityService(  897): Setting Dns servers for network 503 to [/192.168.1.1]
,I/SELinux ( 7972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/Nat464Xlat(  897): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  897): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  897): calling update connectivity
D/ConnectivityService(  897): ignoring duplicate network state non-change
,E/ConnectivityService(  897): updateNetworkInfo()
I/SELinux ( 7972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7972): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  897): ignoring duplicate network state non-change
E/ConnectivityService(  897): updateNetworkInfo()
D/ConnectivityService(  897): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  897): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  897): calling update connectivity
D/ConnectivityService(  897): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  897): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  897):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  897): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  897): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  897): Validated
D/ConnectivityService(  897):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  897):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  897): currentScore = 0, newScore = 60
D/ConnectivityService(  897):    accepting network in place of null
D/ConnectivityService(  897): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1474): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  897): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker(  897): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  897): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  897): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  897): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  897): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  897): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
V/NetworkStats(  897): updateIfacesLocked()
D/NtpTrustedTime(  897): currentTimeMillis() cache hit
V/NetworkStats(  897): performPollLocked(flags=0x1)
,D/SmartBondingService(  897): getSBEnabled() enabled =false
D/EntConnectivity(  897): Not allowed due to - mEnabled false
D/ConnectivityService(  897): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  897): calling update connectivity
D/ConnectivityService(  897):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkStatsFactory(  897): UpdateStatsForKnox
D/ConnectivityService(  897):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  897): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/SmartBondingService(  897): getSBEnabled() enabled =false
D/SmartBondingService(  897): getSBEnabled() enabled =false
,D/ConnectivityService(  897): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,V/NetworkStats(  897): performPollLocked() took 2ms
D/NtpTrustedTime(  897): currentTimeMillis() cache hit
,D/SmartBondingService(  897): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
D/ConnectivityService(  897): identical MTU - not setting
D/ConnectivityService(  897): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  897): updateSourceRoutes : add source routing for type : 1
V/        (  278): QcRouteController
D/ConnectivityService(  897): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
,D/NtpTrustedTime(  897): currentTimeMillis() cache hit
D/NtpTrustedTime(  897): currentTimeMillis() cache hit
D/NtpTrustedTime(  897): currentTimeMillis() cache hit
V/NetworkStats(  897): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  897): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/TimaKeyStoreProvider( 7972): TimaSignature is unavailable
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/ActivityThread( 7972): Added TimaKeyStore provider
,W/libprocessgroup(  897): failed to open /acct/uid_10003/pid_6976/cgroup.procs: No such file or directory
,V/        (  278): QcRouteController
,D/NtpTrustedTime(  897): currentTimeMillis() cache hit
D/NtpTrustedTime(  897): currentTimeMillis() cache hit
,W/NetworkManagementService(  897): route cmd failed: 
W/NetworkManagementService(  897): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '71 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 71 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  897): '
W/NetworkManagementService(  897): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  897): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  897): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  897): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  897): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  897): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  897): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  897): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  897): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  897): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  897): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  897): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  897): calling update connectivity
D/ConnectivityService(  897):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  897):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  897): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  897): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524295
D/ConnectivityService(  897): calling update connectivity
D/ResourcesManager( 7972): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
D/ConnectivityService(  897):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  897):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  897): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  897): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524295
D/ConnectivityService(  897): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  897):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  897):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  897): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  897): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  897): calling update connectivity
D/ConnectivityService(  897):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  897):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  897): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  897): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
W/ResourcesManager( 7972): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7972): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7972): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/SMD     (  285): DCD ON
,D/QuickConnect( 7972): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect( 7972): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7972): PeriphStartReceiver.onReceive - no need to start
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7993): MountEmulatedStorage()
E/Zygote  ( 7993): v2
I/libpersona( 7993): KNOX_SDCARD checking this for 10163
I/libpersona( 7993): KNOX_SDCARD not a persona
I/ActivityManager(  897): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7993 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager(  897): Killing 7006:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,I/SELinux ( 7993): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7993): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7993): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  897): failed to open /acct/uid_10020/pid_7006/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7993): TimaSignature is unavailable
,D/ActivityThread( 7993): Added TimaKeyStore provider
,D/ResourcesManager( 7993): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7993): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7993): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7993): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7993): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  897): exchangeData() failure , invalid userId
,D/RCPManagerService(  897): exchangeData() failure , invalid userId
,D/RCPManagerService(  897): exchangeData() failure , invalid userId
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/RCPManagerService(  897): exchangeData() failure , invalid userId
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,E/Zygote  ( 8016): MountEmulatedStorage()
,E/Zygote  ( 8016): v2
I/libpersona( 8016): KNOX_SDCARD checking this for 10078
I/libpersona( 8016): KNOX_SDCARD not a persona
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,E/Watchdog(  897): !@Sync 3
I/ActivityManager(  897): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8016 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,I/SELinux ( 8016): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 8016): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8016): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  897): exchangeData() failure , invalid userId
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,D/RCPManagerService(  897): exchangeData() failure , invalid userId
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,D/TimaKeyStoreProvider( 8016): TimaSignature is unavailable
,D/ActivityThread( 8016): Added TimaKeyStore provider
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7571): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7571): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7571): StateMachine : Current State = 1
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  897): Killing 6984:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
D/SecurityLogAgent( 7571): StateMachine : Changed Current State = 1
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7993): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_6984/cgroup.procs: No such file or directory
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/art     (  897): Explicit concurrent mark sweep GC freed 80357(4MB) AllocSpace objects, 13(533KB) LOS objects, 30% free, 36MB/52MB, paused 1.332ms total 105.658ms
,I/ActivityManager(  897): Killing 7024:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,D/ResourcesManager( 8016): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/com.peel.receiver.ConnectivityActionReceiver( 5595): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5595): 
D/com.peel.receiver.ConnectivityActionReceiver( 5595): 
D/com.peel.receiver.ConnectivityActionReceiver( 5595): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5595): 
D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5595): 
D/com.peel.receiver.ConnectivityActionReceiver( 5595): 
D/com.peel.receiver.ConnectivityActionReceiver( 5595):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5595): 
D/com.peel.receiver.ConnectivityActionReceiver( 5595): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5595): 
D/com.peel.receiver.ConnectivityActionReceiver( 5595): 
D/com.peel.receiver.ConnectivityActionReceiver( 5595): last run: 1450201652402 -- System.currentTimeMillis()-last_run: 36595676
D/com.peel.receiver.ConnectivityActionReceiver( 5595): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5595): ... skip last_72_check
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 8016): onCreate
,D/BadgeProvider( 8016): DatabaseHelper
,E/Zygote  ( 8034): MountEmulatedStorage()
E/Zygote  ( 8034): v2
I/libpersona( 8034): KNOX_SDCARD checking this for 10178
I/libpersona( 8034): KNOX_SDCARD not a persona
,I/ActivityManager(  897): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8034 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  897): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 8034): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8034): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8034): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  897): failed to open /acct/uid_10112/pid_7024/cgroup.procs: No such file or directory
,D/BadgeProvider( 8016): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 8016): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 8016): sendNotify, [notify] : null
D/BadgeProvider( 8016): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 8016): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 8016): update, [UpdateCount] : 1
,D/Launcher.Model( 1497): reloadBadges entered.
,D/TimaKeyStoreProvider( 8034): TimaSignature is unavailable
,D/ActivityThread( 8034): Added TimaKeyStore provider
,D/ConnectivityService(  897): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ResourcesManager( 8034): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  897): MasterInitialState.processMessage what=3
,D/SmartBondingService(  897): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  897): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  897): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  897): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  897): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  897): getSBEnabled() enabled =false
D/SmartBondingService(  897): getSBEnabled() enabled =false
D/SmartBondingService(  897): getSBEnabled() enabled =false
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  897): CLocinfo wifi true 
D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  897): getNetworkEnabled : wifi : true mobile : true
D/accuweather( 2164): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7158): [#DCM#] [DCM_Performance] onReceive completed in time  177 microsec. 
,I/DBG_DM  ( 3795): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/SystemBroadcastReceiver( 7158): [#DCM#] Calling notifyListeners. 
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DCMController( 7158): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7158): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3795): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ContextImpl( 2230): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2230): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DatabaseRebuilderTask( 7158): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,I/NetworkMonitor( 5361): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FrameworkService( 7158): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7158): [#DCM#] onCreate FrameworkService end 
,I/DCMConfig( 7158): [#DCM#] getSuccessState = true
,I/FrameworkService( 7158): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
I/IntentHandler( 7158): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  897): mCursor = null
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemUtils( 7158): [#DCM#] LM: false,AM:677154816
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DCMThreadPoolExecutor( 7158): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7158): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@10afcc9c is submitted
I/FrameworkService( 7158): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 20193 mirosec. 
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DatabaseRebuilderTask( 7158): [#DCM#] createLuceneReader done 
,I/DatabaseRebuilderTask( 7158): [#DCM#] resyncLocation   
I/DatabaseRebuilderTask( 7158): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DatabaseRebuilderTask( 7158): [#DCM#] topDocs hits = 0
,I/DatabaseRebuilderTask( 7158): [#DCM#] No of Location data to be added:  0
,I/DatabaseRebuilderTask( 7158): [#DCM#] releaseLuceneReader done 
I/DatabaseRebuilderTask( 7158): [#DCM#] Starting media manager do operation 
I/SystemUtils( 7158): [#DCM#] setHeavySharedPref set as  false
,D/ChimeraCfgMgr( 2412): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/IntentHandler( 7158): [#DCM#] Stopping service with ids up to  1
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2412): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/DCMThreadPoolExecutor( 7158): [#DCM#] afterExecute FutureTask
I/DCMController( 7158): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@10afcc9c
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7135): notifyNetworkActivated
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 7135): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  897): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2412): [AccountUtils] Account not ready
W/Kids    ( 2412): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2412): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2412): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2412): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2412): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2412): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2412): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2412): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2412): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2412): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2412): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2412): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,D/hcjo    ( 7135): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7135): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7135): exit::IDLE
D/InitializeManagerStateMachine( 7135): entry::NETWORK_CHECK
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7135): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7135): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7135): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7135): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7135): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7135): entry::SUCCESS
D/hcjo    ( 7135): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1300): Starting #8
,I/Hs20UtilService( 1300): Message received 5007
E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,D/hcjo    ( 7135): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7135): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7135): exit::SUCCESS
D/InitializeManagerStateMachine( 7135): entry::IDLE
,I/ActivityManager(  897): Killing 7039:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,I/Hs20UtilService( 1300): Starting #9
,I/Hs20UtilService( 1300): Message received 5007
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1300): Starting #10
,I/Hs20UtilService( 1300): Message received 5007
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,W/libprocessgroup(  897): failed to open /acct/uid_10118/pid_7039/cgroup.procs: No such file or directory
,I/Hs20UtilService( 1300): Starting #11
,I/Hs20UtilService( 1300): Message received 5007
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  897): callSECApi what=220
,D/WifiStateMachine(  897): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 7640): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7640): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7640): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7640): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/DIAGMON_AGENT( 7678): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7678): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService(  897): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=897
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PowerManagerService(  897): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
D/lights  (  897): lcd : 8 +
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/lights  (  897): lcd : 8 -
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
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
,I/FOTA_Client( 7699): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7699): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/FOTA_Client( 7699): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7699): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7699): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7718): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7718): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450238248560
,I/KLMS-2.4.503: ( 7718): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7718): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7718): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7718): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/KLMS-2.4.503: ( 7718): StateImplV2(): networkChangeListener().END
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SO_AGENT( 7733): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
E/SPPClientService( 7780): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7797): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7797): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7797): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7797): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7797): [OR] == isSIMCardReady false ==
D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7797): [SCU] == networkStateCheck == true
I/SA      ( 7797): [DM] getCountryCodeFromCSC : DE
I/SA      ( 7797): isChinaCountryCode : false
I/SA      ( 7797): [SCU] is ChinestModel Data Restricted   : false
,I/SA      ( 7797): [OR] == networkStateCheck true ==
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SA      ( 7797): [OR] GetMyCountryZoneTask
,I/SA      ( 7797): [OR] onReceive END
,I/SA      ( 7797): [SRS] prepareGetMyCountryZone
,I/SA      ( 7797): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7797): [SSP] query invoked
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7797): [TPMU] GetMccFromDB : null
,D/ConnectivityService(  897): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/accuweather( 7337): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7337): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
I/SA      ( 7797): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 7797): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 7821): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7821): premStatus:2
,I/KnoxUsageLogPro( 7821): isEulaShown : false
I/KnoxUsageLogPro( 7821): KnoxUsageReceiver onReceive : not Processible, just return
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/Headlines( 5491): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5491): getCountryCode(): countryCode = DE
,D/Headlines( 5491): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5491): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5491): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5491): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5491): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5491): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5491): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/File    ( 7797): fail readDirectory() errno=2
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/QuickConnect( 7972): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7972): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7972): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  897): exchangeData() failure , invalid userId
,D/RCPManagerService(  897): exchangeData() failure , invalid userId
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7571): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7571): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7571): StateMachine : Current State = 1
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7571): StateMachine : Changed Current State = 1
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/com.peel.receiver.ConnectivityActionReceiver( 5595): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 5595): 
D/com.peel.receiver.ConnectivityActionReceiver( 5595): 
D/com.peel.receiver.ConnectivityActionReceiver( 5595): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5595): 
D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5595): 
D/com.peel.receiver.ConnectivityActionReceiver( 5595): 
D/com.peel.receiver.ConnectivityActionReceiver( 5595):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5595): 
D/com.peel.receiver.ConnectivityActionReceiver( 5595): has active network... run services...
,D/com.peel.receiver.ConnectivityActionReceiver( 5595): 
D/com.peel.receiver.ConnectivityActionReceiver( 5595): 
D/com.peel.receiver.ConnectivityActionReceiver( 5595): last run: 1450201652402 -- System.currentTimeMillis()-last_run: 36596322
D/com.peel.receiver.ConnectivityActionReceiver( 5595): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5595): ... skip last_72_check
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ChimeraCfgMgr( 2412): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7135): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7135): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7135): exit::IDLE
D/InitializeManagerStateMachine( 7135): entry::NETWORK_CHECK
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7135): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7135): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7135): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7135): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7135): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7135): entry::SUCCESS
D/hcjo    ( 7135): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7135): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7135): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7135): exit::SUCCESS
D/InitializeManagerStateMachine( 7135): entry::IDLE
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/art     ( 1693): Explicit concurrent mark sweep GC freed 32789(2046KB) AllocSpace objects, 21(1701KB) LOS objects, 39% free, 17MB/29MB, paused 438us total 27.966ms
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2412): [AccountUtils] Account not ready
W/Kids    ( 2412): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2412): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2412): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2412): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2412): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2412): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2412): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2412): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2412): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2412): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2412): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2412): 	at java.lang.Thread.run(Thread.java:818)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/SA      ( 7797): [RC New] Execute method=[GET] start
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
I/SA      ( 7797): [RC New] Security=[true]
,I/System.out( 7797): Thread-1285(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7797): Thread-1285(ApacheHTTPLog):isShipBuild true
,I/System.out( 7797): Thread-1285(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7507): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7507): 
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/SA      ( 7797): [RC New] [v2liruge] api execute + 825
,I/SA      ( 7797): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7797): AsyncTask #1 calls detatch()
,I/SA      ( 7797): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7797): [OCP] update openData : PL
,I/SA      ( 7797): [TPMU] getNetworkMcc : 
,I/SA      ( 7797): [SCU] saveMccToPreferece Start
I/SA      ( 7797): [SCU] RegionMCC : 260
I/SA      ( 7797): [SSP] query invoked
,I/SA      ( 7797): [TPMU] GetMccFromDB : null
I/SA      ( 7797): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7797): [SCU] saveMccToPreferece End
,I/SA      ( 7797): [RC New] executeRequest [v2liruge] end. 923
,I/SA      ( 7797): [RC New] Execute end
,I/SA      ( 7797): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 7797): [OR] GetMyCountryZoneTask Success
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,V/AlarmManager(  897): waitForAlarm result :8
,D/PowerManagerService(  897): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  897): [PWL] On : 76356 (30001 ms ago)
I/PowerManagerService(  897): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
I/PowerManagerService(  897): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=897, ws=WorkSource{10059}) (elapsedTime=1945)
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dhcpcd  ( 7768): wlan0: sending IPv6 Router Solicitation
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
D/ResourcesManager( 1693): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/Search.LoginHelper( 1575): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,E/SMD     (  285): DCD ON
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  897): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  897): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  897): SIOP:: AP = 400, PST = 423, CUR = 300
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PowerManagerService(  897): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 897) eventTime = 107908
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
D/PowerManagerService(  897): [s] UserActivityState : 4 -> 1
I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
D/PowerManagerService(  897): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=897 (0x0)
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
D/PowerManagerService(  897): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=897, ws=WorkSource{10059}) (elapsedTime=3497)
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
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
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
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
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/GAV4    ( 7871): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
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
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/SurfaceFlinger(  249): id=16 Removed Toast (8/8)
,I/SurfaceFlinger(  249): id=16 Removed Toast (-2/8)
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7640): mConnectivityHandler : connected
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7640): [hasSamungAccount] - No Samsung Account
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CSTORAGE( 7640): ================================================
I/CSTORAGE( 7640):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 7640): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7640): [GetString-S]
E/art     ( 7640): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 7640): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7640): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 7640): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7640): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7640): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7640): [ensureRegistration] - No Samsung account
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/GCM     ( 1693): Connected
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1693): Message class com.google.f.a.a.p
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7768): wlan0: sending IPv6 Router Solicitation
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth,
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false),
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 7135): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7135): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7135): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7135): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7135): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7135): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7135): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7135): entry::IDLE
E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7768): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7768): wlan0: no IPv6 Routers available
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 7135): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 7135): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7135): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 7135): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7135): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7135): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7135): entry::IDLE
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/FactoryTest( 6490): Not factory mode
D/FactoryTest( 6490): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6490): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6490): still no open session command from host, so toast
,W/ContextImpl( 6490): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 6490): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6490): Timeline: Activity_launch_request id:com.android.settings time:115391
,E/PersonaManagerService(  897): inState():  stateMachine is null !!
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  897): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  897): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 897  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  897): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SQLiteSecureOpenHelper( 3527): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3527): getDatabaseLocked(b,b,pwd)...
,E/MTPRx   ( 6490): started activity for popup
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/ResourcesManager( 6490): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6490): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
W/ResourcesManager( 6490): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,W/ResourcesManager( 6490): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6490): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
W/ResourcesManager( 6490): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6490): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6490): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6490): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/ActivityManager(  897): Invalid thumbnail dimensions: 576x576
,D/InputMethodManagerService(  897): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  897): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@43e9b1f attribute=null, token = android.os.BinderProxy@2088c8b5
,I/SQLiteSecureOpenHelper( 3527): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3527): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6490): dev.kiessupport is : TRUE
,D/Activity( 6490): performCreate Call secproduct feature valuefalse
D/Activity( 6490): performCreate Call debug elastic valuetrue
,E/SMD     (  285): DCD ON
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
D/LockPatternUtilsCache( 1169): value : false
,D/ActivityManager(  897): post active user change for 0
D/KnoxTimeoutHandler(  897): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  897): handleActiveUserChange for user 0
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/Timeline( 7507): Timeline: Activity_idle id: android.os.BinderProxy@3460251f time:115647
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  897): SIOP:: AP = 360, PST = 412, CUR = 300
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  897): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 897  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  897): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  897): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 897  pkgName : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/SMD     (  285): DCD ON
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  897): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 897  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/ActivityManager(  897): Waited long enough for: ServiceRecord{39ec3a0c u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
V/AlarmManager(  897): waitForAlarm result :4
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6659): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6659): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6659): [1] 5.onFinished: Scheduling replication attempt 3.
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  897): SIOP:: AP = 340, PST = 398, CUR = 300
,D/X       (  897): broadcastSiopLevelIntent:: currentSiopLevel = -1
,I/SystemBroadcastReceiver( 7158): [#DCM#] [DCM_Performance] onReceive completed in time  853 microsec. 
,D/ContentApp( 1222):  LEVEL : -1
,I/SystemBroadcastReceiver( 7158): [#DCM#] Calling notifyListeners. 
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,I/DCMPolicyManager( 7158): [#DCM#] onReceive action = EVENT_SIOP
,E/Zygote  ( 8167): MountEmulatedStorage()
,E/Zygote  ( 8167): v2
I/libpersona( 8167): KNOX_SDCARD checking this for 10054
,I/libpersona( 8167): KNOX_SDCARD not a persona
I/ActivityManager(  897): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8167 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 8167): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8167): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8167): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  316): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 510us total 29.684ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 451us total 15.179ms
,E/SMD     (  285): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 399us total 17.969ms
,D/TimaKeyStoreProvider( 8167): TimaSignature is unavailable
,D/ActivityThread( 8167): Added TimaKeyStore provider
,D/ResourcesManager( 8167): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
W/ResourcesManager( 8167): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
W/ResourcesManager( 8167): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
W/ResourcesManager( 8167): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8167): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8167): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 8167): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8167): core_num = 4
,W/linker  ( 8167): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8167): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,D/videowall-Global( 8167): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
D/videowall-Global( 8167): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8167):  SIOP_LEVEL: -1
,I/ActivityManager(  897): Killing 7055:com.samsung.helphub/1000 (adj 15): bgCount ##41
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,W/libprocessgroup(  897): failed to open /acct/uid_1000/pid_7055/cgroup.procs: No such file or directory
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!,
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  897): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  897): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  897): lcd : 2 +
,D/lights  (  897): lcd : 2 -
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/lights  (  897): lcd : 1 +
,D/lights  (  897): lcd : 1 -
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/SMD     (  285): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/Watchdog(  897): !@Sync 4
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,V/AlarmManager(  897): waitForAlarm result :8
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/SMD     (  285): DCD ON
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/SSRM:m  (  897): SIOP:: AP = 330, PST = 382, CUR = 300
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
,D/DisplayPowerController(  897): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  897): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  897): Nap time (uid 1000)...
I/PowerManagerService(  897): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  897): Going to sleep due to screen timeout (uid 1000)...
D/InputManager-JNI(  897): setDeviceInteractive: 0
,D/PowerManagerService(  897): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  897): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService(  897): handleSandman : startDream()
,D/InputManager-JNI(  897): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,E/PowerManagerService(  897): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  897): Sleeping (uid 1000)...
,D/PowerManagerService(  897): [s] UserActivityState : 4 -> 0
,D/PowerManagerService(  897): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService(  897): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  897): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  897): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  897): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService(  897): 	.unregisterCallback : 1, client=
,D/SContextService(  897): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3fc12312, Service = Auto Rotation, used = 1
,W/CAE     (  897): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  897): stop(ContextProvider.java:149)
,V/CAE     (  897): clear(AutoRotationRunner.java:182)
,V/CAE     (  897): disable(AutoRotationRunner.java:171)
,I/CAE     (  897): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,,
,D/SensorHubManager(  897): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  297): sendContextData: -78, 7, 0, 0
,D/CAE     (  897): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  897): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  897): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  897): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  897): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  897): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  897): removeSContextService() : service = Auto Rotation
,D/SContextService(  897): ===== SContext Service List =====
D/SContextManager(  897):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@381b3729, service=Auto Rotation
,D/KeyguardViewMediator( 1169): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1169): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1169): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1169): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/KeyguardViewMediator( 1169): timeout : 5000
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SQLiteSecureOpenHelper( 3527): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3527): getDatabaseLocked(b,b,pwd)...
,D/DisplayPowerController(  897): ColorFade: onAnimationStart
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 0
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 0
,D/lights  (  897): lcd : 0 +
,D/DisplayPowerController(  897): getFinalBrightness : 8 -> 0
,D/lights  (  897): lcd : 0 -
,D/KeyguardViewMediator( 1169): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1169): handleNotifyScreenOff
,D/LightsService(  897): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 897) 
D/LightsService(  897): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  897): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  897): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  897): unregisterListener ::   
D/lights  (  897): led_pattern : 5 +
,D/BatteryService(  897): turn on LED for fully charged
,D/lights  (  897): led_pattern : 5 -
,D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore in!
,I/CAE     (  897): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/WifiStateMachine(  897): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  897): CMD_RSSI_POLL : out!
I/CAE     (  897): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  897): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  897): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  297): sendContextData: -76, 13, -46, 0
,I/CAE     (  897): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 3, 58, 2,
,D/SensorHubManager(  897): SendSensorHubData: send data = -63, 14, 3, 58, 2
D/Sensorhubs(  297): sendContextData: -63, 14, 3, 58, 2
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  897):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  897): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  897): handleScreenStateChanged Exit: false
,D/NotificationService(  897): ACTION_SCREEN_OFF
,D/LightsService(  897): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 897) 
D/LightsService(  897): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  897): [SvcLED]  onSensorChanged::light value = 0
,E/WifiStateMachine(  897): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  897): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  897): do suspend true
,D/SensorManager(  897): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  897): unregisterListener ::   
D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  290): adev_set_parameters: enter: screen_state=off
,V/voice   (  290): voice_set_parameters: enter: screen_state=off
V/voice   (  290): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  290): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  290): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  290): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  290): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  897): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  897): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  897): Bridge Server is not available
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1169): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1169): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  897): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  897): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1467): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1169):      ACTION_SCREEN_OFF is finished!!!! 
,E/LightSensor(  897): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  897): mCallbacks.updateBrightness()
D/DisplayPowerController(  897): getFinalBrightness : 8 -> 0
,E/StatusBar( 1169): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1169): dismissHelpPopup 
,D/accuweather( 2164): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2164): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2164): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/DisplayPowerState(  897): !@ ColorFade entry
,D/DisplayPowerController(  897): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  897): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/AutomaticBrightnessController(  897): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  897): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController(  897): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,E/LightSensor(  897): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,D/SensorManager(  897): unregisterListener ::   
,E/Sensors (  897): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  897): unregisterListener ::   
,D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DisplayPowerController(  897): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  897): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
D/DisplayPowerController(  897): getFinalBrightness : 0 -> 0
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,V/ActivityManager(  897): Display changed displayId=0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/SSRM:m  (  897): SIOP:: AP = 330, PST = 371, CUR = 300
,I/SystemBroadcastReceiver( 7158): [#DCM#] [DCM_Performance] onReceive completed in time  237 microsec. 
,I/SystemBroadcastReceiver( 7158): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7158): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 7158): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/StatusBar.NetworkController( 1169): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,W/ActivityManager(  897): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  897): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PowerManagerService(  897): [PWL] sb release: PowerManagerService.Broadcasts
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
,I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1228406016)
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1228406016) wakelock released: 1, error no: 22
I/rmt_storage(  272): 
,I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
D/SurfaceControl(  897): Excessive delay in setPowerMode(): 256ms
D/PowerManagerService(  897): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  897): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  897): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  897): Got set_interactive hint
,I/PowerManagerService(  897): [PWL] Off : 0s ago
,I/PowerManagerService(  897): [PWL]   PowerManagerService.Display: ref count=2
,I/PowerManagerService(  897): [PWL]     mDisplayReady : false
,D/DisplayPowerController(  897): getFinalBrightness : 0 -> 0
D/PowerManagerService(  897): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService(  897): [PWL] sb release: PowerManagerService.Display
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,V/AlarmManager(  897): waitForAlarm result :4
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): stay LED for fully charged
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6659): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6659): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6659): [1] 5.onFinished: Scheduling replication attempt 4.
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardViewMediator( 1169): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/KeyguardViewMediator( 1169): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService(  897): [PWL] Off : 5s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 320, PST = 362, CUR = 300,
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1693): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6629): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at kff.l(PG:132)
E/HttpOperation( 6629): 	at dsf.a(PG:807)
E/HttpOperation( 6629): 	at fhk.a(PG:1126)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 8 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 10 more
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6629): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at kff.l(PG:132)
E/HttpOperation( 6629): 	at ieo.a(PG:43)
E/HttpOperation( 6629): 	at iep.a(PG:93)
E/HttpOperation( 6629): 	at fhn.a(PG:59)
E/HttpOperation( 6629): 	at lex.a(PG:85)
E/HttpOperation( 6629): 	at lex.b(PG:132)
E/HttpOperation( 6629): 	at fhk.a(PG:1146)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 12 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 14 more
,E/ExperimentLoader( 6629): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6629): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6629): 	at kfv.a(PG:65)
E/ExperimentLoader( 6629): 	at kff.u(PG:385)
E/ExperimentLoader( 6629): 	at kfb.a(PG:29)
E/ExperimentLoader( 6629): 	at kff.l(PG:132)
E/ExperimentLoader( 6629): 	at ieo.a(PG:43)
E/ExperimentLoader( 6629): 	at iep.a(PG:93)
E/ExperimentLoader( 6629): 	at fhn.a(PG:59)
E/ExperimentLoader( 6629): 	at lex.a(PG:85)
E/ExperimentLoader( 6629): 	at lex.b(PG:132)
E/ExperimentLoader( 6629): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6629): 	at fhk.a(PG:908)
E/ExperimentLoader( 6629): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6629): 	at ihi.a(PG:22)
E/ExperimentLoader( 6629): 	at kft.a(PG:91)
E/ExperimentLoader( 6629): 	at kfv.a(PG:62)
E/ExperimentLoader( 6629): 	... 12 more
E/ExperimentLoader( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6629): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6629): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6629): 	at ihi.a(PG:19)
E/ExperimentLoader( 6629): 	... 14 more
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6629): [getaccountstatus] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at ixd.a(PG:248)
E/HttpOperation( 6629): 	at ixd.b(PG:206)
E/HttpOperation( 6629): 	at ixd.a(PG:175)
E/HttpOperation( 6629): 	at fig.a(PG:78)
E/HttpOperation( 6629): 	at lex.a(PG:85)
E/HttpOperation( 6629): 	at lex.b(PG:132)
E/HttpOperation( 6629): 	at fhk.a(PG:1146)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 12 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 14 more
,E/EsSyncAdapterService( 6629): Sync failure
E/EsSyncAdapterService( 6629): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6629): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6629): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6629): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6629): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6629): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6629): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6629): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6629): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6629): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6629): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6629): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6629): 	... 10 more
E/EsSyncAdapterService( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6629): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6629): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6629): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6629): 	... 12 more
E/EsSyncAdapterService( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6629): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6629): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6629): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6629): 	... 14 more
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 125926, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  897): Explicit concurrent mark sweep GC freed 73343(4MB) AllocSpace objects, 29(3MB) LOS objects, 30% free, 36MB/52MB, paused 1.534ms total 111.781ms
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  897): mCursor = null
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,I/PowerManagerService(  897): [PWL] Off : 15s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  897): SIOP:: AP = 320, PST = 353, CUR = 300
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager(  897): waitForAlarm result :4
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6659): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6659): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6659): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 5
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 310, PST = 344, CUR = 300
,I/PowerManagerService(  897): [PWL] Off : 30s ago
,E/SMD     (  285): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 310, PST = 338, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7428): Starting books sync, d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1693): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7428): null auth token
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,V/AlarmManager(  897): waitForAlarm result :4
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
,W/ApiaryClient( 7428): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4779149983222916801&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/VacuumService( 1693): Vacuum at: now=1450238326954 tag=VacuumService
,I/GoogleURLConnFactory( 1693): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/Uploader( 1693): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1693): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1693): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1693): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/System.out( 1693): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1693): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1693): (HTTPLog)-Thread-207-209160612: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1693): Tagging socket 60 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,I/qtaguid ( 1693): Tagging socket 64 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6659): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6659): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6659): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1693): No account for auth token provided
,I/qtaguid ( 1693): Tagging socket 60 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,W/Uploader( 1693): No account for auth token provided
,I/qtaguid ( 1693): Tagging socket 60 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1693): No account for auth token provided
,I/qtaguid ( 1693): Tagging socket 60 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1693): No account for auth token provided
,I/qtaguid ( 1693): Tagging socket 60 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7428): null auth token
,W/Uploader( 1693): No account for auth token provided
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 1693): Tagging socket 60 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
W/ApiaryClient( 7428): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4779149983222916801&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Uploader( 1693):  no longer exists, so no auth token.
,I/qtaguid ( 1693): Tagging socket 60 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7428): null auth token
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
,W/ApiaryClient( 7428): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4779149983222916801&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/BooksSync( 7428): Soft error
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4779149983222916801&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7428): Headers suppressed
E/BooksSync( 7428): 
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7428): Sync error
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4779149983222916801&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7428): Headers suppressed
E/BooksSync( 7428): 
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7428): Finished books sync
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 162395, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  897): mCursor = null
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6629): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at kff.l(PG:132)
E/HttpOperation( 6629): 	at dsf.a(PG:807)
E/HttpOperation( 6629): 	at fhk.a(PG:1126)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 8 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 10 more
,I/art     ( 1693): Explicit concurrent mark sweep GC freed 50814(2MB) AllocSpace objects, 68(4MB) LOS objects, 39% free, 18MB/30MB, paused 715us total 42.383ms
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1693): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6629): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at kff.l(PG:132)
E/HttpOperation( 6629): 	at ieo.a(PG:43)
E/HttpOperation( 6629): 	at iep.a(PG:93)
E/HttpOperation( 6629): 	at fhn.a(PG:59)
E/HttpOperation( 6629): 	at lex.a(PG:85)
E/HttpOperation( 6629): 	at lex.b(PG:132)
E/HttpOperation( 6629): 	at fhk.a(PG:1146)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 12 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 14 more
,E/ExperimentLoader( 6629): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6629): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6629): 	at kfv.a(PG:65)
E/ExperimentLoader( 6629): 	at kff.u(PG:385)
E/ExperimentLoader( 6629): 	at kfb.a(PG:29)
E/ExperimentLoader( 6629): 	at kff.l(PG:132)
E/ExperimentLoader( 6629): 	at ieo.a(PG:43)
E/ExperimentLoader( 6629): 	at iep.a(PG:93)
E/ExperimentLoader( 6629): 	at fhn.a(PG:59)
E/ExperimentLoader( 6629): 	at lex.a(PG:85)
E/ExperimentLoader( 6629): 	at lex.b(PG:132)
E/ExperimentLoader( 6629): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6629): 	at fhk.a(PG:908)
E/ExperimentLoader( 6629): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6629): 	at ihi.a(PG:22)
E/ExperimentLoader( 6629): 	at kft.a(PG:91)
E/ExperimentLoader( 6629): 	at kfv.a(PG:62)
E/ExperimentLoader( 6629): 	... 12 more
E/ExperimentLoader( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6629): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6629): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6629): 	at ihi.a(PG:19)
E/ExperimentLoader( 6629): 	... 14 more
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6629): [getaccountstatus] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at ixd.a(PG:248)
E/HttpOperation( 6629): 	at ixd.b(PG:206)
E/HttpOperation( 6629): 	at ixd.a(PG:175)
E/HttpOperation( 6629): 	at fig.a(PG:78)
E/HttpOperation( 6629): 	at lex.a(PG:85)
E/HttpOperation( 6629): 	at lex.b(PG:132)
E/HttpOperation( 6629): 	at fhk.a(PG:1146)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 12 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 14 more
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/EsSyncAdapterService( 6629): Sync failure
E/EsSyncAdapterService( 6629): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6629): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6629): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6629): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6629): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6629): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6629): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6629): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6629): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6629): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6629): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6629): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6629): 	... 10 more
E/EsSyncAdapterService( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6629): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6629): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6629): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6629): 	... 12 more
E/EsSyncAdapterService( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6629): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6629): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6629): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6629): 	... 14 more
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 184531, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  897): mCursor = null
,W/ProcessCpuTracker(  897): Skipping unknown process pid 8330
,W/ProcessCpuTracker(  897): Skipping unknown process pid 8333
,I/art     (  897): Explicit concurrent mark sweep GC freed 36964(1902KB) AllocSpace objects, 18(743KB) LOS objects, 30% free, 36MB/52MB, paused 1.940ms total 184.533ms
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService(  897): [PWL] Off : 50s ago
,D/SSRM:m  (  897): SIOP:: AP = 310, PST = 333, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3234): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 6
,V/AlarmManager(  897): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 310, PST = 324, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 318, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate,
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  897): [PWL] Off : 75s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 314, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 7
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 311, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 308, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7428): Starting books sync, d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1693): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7428): null auth token
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
,W/ApiaryClient( 7428): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1839114197955160649&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  897): [PWL] Off : 105s ago
,I/PowerManagerService(  897): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  897): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  897): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=897, ws=WorkSource{10082}) (elapsedTime=1113)
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7428): null auth token
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
,W/ApiaryClient( 7428): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1839114197955160649&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7428): null auth token
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
,W/ApiaryClient( 7428): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1839114197955160649&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7428): Soft error
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1839114197955160649&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7428): Headers suppressed
E/BooksSync( 7428): 
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7428): Sync error
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1839114197955160649&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7428): Headers suppressed
E/BooksSync( 7428): 
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7428): Finished books sync
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 216731, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  897): mCursor = null
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 306, CUR = 300
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 8
,V/AlarmManager(  897): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 304, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 303, CUR = 300
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3234): Disconnected process message: 10
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6629): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at kff.l(PG:132)
E/HttpOperation( 6629): 	at dsf.a(PG:807)
E/HttpOperation( 6629): 	at fhk.a(PG:1126)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 8 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 10 more
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6629): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at kff.l(PG:132)
E/HttpOperation( 6629): 	at ieo.a(PG:43)
E/HttpOperation( 6629): 	at iep.a(PG:93)
E/HttpOperation( 6629): 	at fhn.a(PG:59)
E/HttpOperation( 6629): 	at lex.a(PG:85)
E/HttpOperation( 6629): 	at lex.b(PG:132)
E/HttpOperation( 6629): 	at fhk.a(PG:1146)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 12 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 14 more
,E/ExperimentLoader( 6629): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6629): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6629): 	at kfv.a(PG:65)
E/ExperimentLoader( 6629): 	at kff.u(PG:385)
E/ExperimentLoader( 6629): 	at kfb.a(PG:29)
E/ExperimentLoader( 6629): 	at kff.l(PG:132)
E/ExperimentLoader( 6629): 	at ieo.a(PG:43)
E/ExperimentLoader( 6629): 	at iep.a(PG:93)
E/ExperimentLoader( 6629): 	at fhn.a(PG:59)
E/ExperimentLoader( 6629): 	at lex.a(PG:85)
E/ExperimentLoader( 6629): 	at lex.b(PG:132)
E/ExperimentLoader( 6629): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6629): 	at fhk.a(PG:908)
E/ExperimentLoader( 6629): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6629): 	at ihi.a(PG:22)
E/ExperimentLoader( 6629): 	at kft.a(PG:91)
E/ExperimentLoader( 6629): 	at kfv.a(PG:62)
E/ExperimentLoader( 6629): 	... 12 more
E/ExperimentLoader( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6629): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6629): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6629): 	at ihi.a(PG:19)
E/ExperimentLoader( 6629): 	... 14 more
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6629): [getaccountstatus] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at ixd.a(PG:248)
E/HttpOperation( 6629): 	at ixd.b(PG:206)
E/HttpOperation( 6629): 	at ixd.a(PG:175)
E/HttpOperation( 6629): 	at fig.a(PG:78)
E/HttpOperation( 6629): 	at lex.a(PG:85)
E/HttpOperation( 6629): 	at lex.b(PG:132)
E/HttpOperation( 6629): 	at fhk.a(PG:1146)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 12 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 14 more
,E/EsSyncAdapterService( 6629): Sync failure
E/EsSyncAdapterService( 6629): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6629): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6629): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6629): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6629): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6629): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6629): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6629): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6629): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6629): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6629): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6629): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6629): 	... 10 more
E/EsSyncAdapterService( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6629): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6629): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6629): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6629): 	... 12 more
E/EsSyncAdapterService( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6629): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6629): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6629): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6629): 	... 14 more
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 250989, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  897): mCursor = null
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  897): [PWL] Off : 140s ago
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 302, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 9
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 301, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  897): stay LED for fully charged
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 299, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 298, CUR = 300
,E/SMD     (  285): DCD ON
,D/TimaService(  897): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  897): TimaServiceHandler.handleMessage what =1
,D/TimaService(  897): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  897): initializing...
,I/TLC_TIMA_PKM_initialize(  897): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  897): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  897): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  897): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  897): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  897): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  897): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  897): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  897): App is not loaded in QSEE
,D/QSEECOMAPI: (  897): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  897): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  897): Trustlet response is completed
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,V/AlarmManager(  897): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  897): [PWL] Off : 180s ago
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 298, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 297, CUR = 300
,I/jxcore-log( 7507): Connected to the server!
I/jxcore-log( 7507): 
,I/chromium( 7507): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  285): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7428): Starting books sync, d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7428): null auth token
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
,W/ApiaryClient( 7428): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=605430493059429855&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,V/AlarmManager(  897): waitForAlarm result :4
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8455): MountEmulatedStorage()
,I/ActivityManager(  897): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8455 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 8455): v2
I/libpersona( 8455): KNOX_SDCARD checking this for 10081
I/libpersona( 8455): KNOX_SDCARD not a persona
,I/SELinux ( 8455): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8455): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8455): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8455): TimaSignature is unavailable
,D/ActivityThread( 8455): Added TimaKeyStore provider
,D/ResourcesManager( 8455): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,E/SMD     (  285): DCD ON
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7428): null auth token
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
,W/ApiaryClient( 7428): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=605430493059429855&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7428): null auth token
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
,W/ApiaryClient( 7428): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=605430493059429855&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7428): Soft error
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=605430493059429855&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7428): Headers suppressed
E/BooksSync( 7428): 
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7428): Sync error
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=605430493059429855&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7428): Headers suppressed
E/BooksSync( 7428): 
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7428): Finished books sync
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  897): Killing 7097:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 307646, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  897): failed to open /acct/uid_10166/pid_7097/cgroup.procs: No such file or directory
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  897): Explicit concurrent mark sweep GC freed 50943(3MB) AllocSpace objects, 58(1513KB) LOS objects, 30% free, 36MB/52MB, paused 1.599ms total 134.649ms
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  897): mCursor = null
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  897): SIOP:: AP = 300, PST = 297, CUR = 300
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 11
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 296, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1693): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/PlayEventLogger( 6659): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6659): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6659): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6659): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6659): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6659): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6659): 	at android.os.Binder.execTransact(Binder.java:446)
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/System  ( 6659): Ignoring header User-Agent because its value was null.
,I/System.out( 6659): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6659): (HTTPLog)-Static: isShipBuild true
I/System.out( 6659): (HTTPLog)-Thread-1088-258702592: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  897): [PWL] Off : 225s ago
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 12
,V/AlarmManager(  897): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 293, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6629): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at kff.l(PG:132)
E/HttpOperation( 6629): 	at dsf.a(PG:807)
E/HttpOperation( 6629): 	at fhk.a(PG:1126)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 8 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 10 more
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1693): Explicit concurrent mark sweep GC freed 39220(2MB) AllocSpace objects, 29(2MB) LOS objects, 40% free, 18MB/30MB, paused 1.648ms total 85.305ms
,D/ResourcesManager( 1693): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6629): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at kff.l(PG:132)
E/HttpOperation( 6629): 	at ieo.a(PG:43)
E/HttpOperation( 6629): 	at iep.a(PG:93)
E/HttpOperation( 6629): 	at fhn.a(PG:59)
E/HttpOperation( 6629): 	at lex.a(PG:85)
E/HttpOperation( 6629): 	at lex.b(PG:132)
E/HttpOperation( 6629): 	at fhk.a(PG:1146)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 12 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 14 more
,E/ExperimentLoader( 6629): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6629): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6629): 	at kfv.a(PG:65)
E/ExperimentLoader( 6629): 	at kff.u(PG:385)
E/ExperimentLoader( 6629): 	at kfb.a(PG:29)
E/ExperimentLoader( 6629): 	at kff.l(PG:132)
E/ExperimentLoader( 6629): 	at ieo.a(PG:43)
E/ExperimentLoader( 6629): 	at iep.a(PG:93)
E/ExperimentLoader( 6629): 	at fhn.a(PG:59)
E/ExperimentLoader( 6629): 	at lex.a(PG:85)
E/ExperimentLoader( 6629): 	at lex.b(PG:132)
E/ExperimentLoader( 6629): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6629): 	at fhk.a(PG:908)
E/ExperimentLoader( 6629): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6629): 	at ihi.a(PG:22)
E/ExperimentLoader( 6629): 	at kft.a(PG:91)
E/ExperimentLoader( 6629): 	at kfv.a(PG:62)
E/ExperimentLoader( 6629): 	... 12 more
E/ExperimentLoader( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6629): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6629): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6629): 	at ihi.a(PG:19)
E/ExperimentLoader( 6629): 	... 14 more
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6629): [getaccountstatus] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at ixd.a(PG:248)
E/HttpOperation( 6629): 	at ixd.b(PG:206)
E/HttpOperation( 6629): 	at ixd.a(PG:175)
E/HttpOperation( 6629): 	at fig.a(PG:78)
E/HttpOperation( 6629): 	at lex.a(PG:85)
E/HttpOperation( 6629): 	at lex.b(PG:132)
E/HttpOperation( 6629): 	at fhk.a(PG:1146)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 12 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 14 more
,E/EsSyncAdapterService( 6629): Sync failure
E/EsSyncAdapterService( 6629): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6629): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6629): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6629): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6629): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6629): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6629): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6629): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6629): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6629): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6629): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6629): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6629): 	... 10 more
E/EsSyncAdapterService( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6629): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6629): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6629): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6629): 	... 12 more
E/EsSyncAdapterService( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6629): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6629): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6629): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6629): 	... 14 more
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 401635, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2858): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2858): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk,
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  897): mCursor = null
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 13
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 292, CUR = 300
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService(  897): [PWL] Off : 275s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 14
,V/AlarmManager(  897): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7428): Starting books sync, d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1693): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7428): null auth token
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
,W/ApiaryClient( 7428): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized,
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6658885662405386711&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  285): DCD ON
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7428): null auth token
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
,W/ApiaryClient( 7428): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6658885662405386711&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  897): !@Sync 15
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7428): null auth token
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
,W/ApiaryClient( 7428): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6658885662405386711&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7428): Soft error
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6658885662405386711&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7428): Headers suppressed
E/BooksSync( 7428): 
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7428): Sync error
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6658885662405386711&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7428): Headers suppressed
E/BooksSync( 7428): 
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7428): Finished books sync
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 459192, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  897): mCursor = null
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/PowerManagerService(  897): [PWL] Off : 330s ago
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/bootchecker(  319): bootchecker wake up!!
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 16
,V/AlarmManager(  897): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 17
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/PowerManagerService(  897): [PWL] Off : 390s ago
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 18
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/Atfwd_Daemon(  326): Stop the daemon....
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 19
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  897): [PWL] Off : 455s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/TimaService(  897): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  897): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  897): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/ActivityManager(  897): Killing 7116:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,W/libprocessgroup(  897): failed to open /acct/uid_10170/pid_7116/cgroup.procs: No such file or directory
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 21
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  897): [PWL] Off : 525s ago
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 22
,V/AlarmManager(  897): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6629): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at kff.l(PG:132)
E/HttpOperation( 6629): 	at dsf.a(PG:807)
E/HttpOperation( 6629): 	at fhk.a(PG:1126)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 8 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 10 more
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6629): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at kff.l(PG:132)
E/HttpOperation( 6629): 	at ieo.a(PG:43)
E/HttpOperation( 6629): 	at iep.a(PG:93)
E/HttpOperation( 6629): 	at fhn.a(PG:59)
E/HttpOperation( 6629): 	at lex.a(PG:85)
E/HttpOperation( 6629): 	at lex.b(PG:132)
E/HttpOperation( 6629): 	at fhk.a(PG:1146)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 12 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 14 more
,E/ExperimentLoader( 6629): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6629): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6629): 	at kfv.a(PG:65)
E/ExperimentLoader( 6629): 	at kff.u(PG:385)
E/ExperimentLoader( 6629): 	at kfb.a(PG:29)
E/ExperimentLoader( 6629): 	at kff.l(PG:132)
E/ExperimentLoader( 6629): 	at ieo.a(PG:43)
E/ExperimentLoader( 6629): 	at iep.a(PG:93)
E/ExperimentLoader( 6629): 	at fhn.a(PG:59)
E/ExperimentLoader( 6629): 	at lex.a(PG:85)
E/ExperimentLoader( 6629): 	at lex.b(PG:132)
E/ExperimentLoader( 6629): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6629): 	at fhk.a(PG:908)
E/ExperimentLoader( 6629): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6629): 	at ihi.a(PG:22)
E/ExperimentLoader( 6629): 	at kft.a(PG:91)
E/ExperimentLoader( 6629): 	at kfv.a(PG:62)
E/ExperimentLoader( 6629): 	... 12 more
E/ExperimentLoader( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6629): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6629): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6629): 	at ihi.a(PG:19)
E/ExperimentLoader( 6629): 	... 14 more
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6629): [getaccountstatus] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at ixd.a(PG:248)
E/HttpOperation( 6629): 	at ixd.b(PG:206)
E/HttpOperation( 6629): 	at ixd.a(PG:175)
E/HttpOperation( 6629): 	at fig.a(PG:78)
E/HttpOperation( 6629): 	at lex.a(PG:85)
E/HttpOperation( 6629): 	at lex.b(PG:132)
E/HttpOperation( 6629): 	at fhk.a(PG:1146)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 12 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 14 more
,E/EsSyncAdapterService( 6629): Sync failure
E/EsSyncAdapterService( 6629): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6629): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6629): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6629): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6629): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6629): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6629): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6629): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6629): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6629): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6629): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6629): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6629): 	... 10 more
E/EsSyncAdapterService( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6629): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6629): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6629): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6629): 	... 12 more
E/EsSyncAdapterService( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6629): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6629): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6629): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6629): 	... 14 more
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 658706, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  897): Explicit concurrent mark sweep GC freed 60682(4MB) AllocSpace objects, 118(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.955ms total 201.322ms
D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  897): mCursor = null
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 23
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/BooksSync( 7428): Starting books sync, d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7428): null auth token
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
,W/ApiaryClient( 7428): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7204776592454705914&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7428): null auth token
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Tagging socket 40 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
,W/ApiaryClient( 7428): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7204776592454705914&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7428): null auth token
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
,W/ApiaryClient( 7428): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7204776592454705914&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7428): Soft error
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7204776592454705914&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7428): Headers suppressed
E/BooksSync( 7428): 
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7428): Sync error
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7204776592454705914&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7428): Headers suppressed
E/BooksSync( 7428): 
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7428): Finished books sync
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 710256, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  897): mCursor = null
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON,
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 24
,V/AlarmManager(  897): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  897): [PWL] Off : 600s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): stay LED for fully charged
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 25
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 26
,V/AlarmManager(  897): waitForAlarm result :8
,V/AlarmManager(  897): waitForAlarm result :4
,D/LightsService(  897): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  897): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/Finsky  ( 6659): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/SensorManager(  897): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6659): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2412): Aggregate from 1450236681350 (log), 1450236681350 (data)
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  897): [SvcLED]  onSensorChanged::light value = 0
E/LightSensor(  897): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  897): unregisterListener ::   
D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  285): DCD ON
,W/Finsky  ( 6659): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1693): Explicit concurrent mark sweep GC freed 38426(2MB) AllocSpace objects, 24(1944KB) LOS objects, 39% free, 18MB/30MB, paused 560us total 42.853ms
,W/Finsky  ( 6659): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6659): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6659): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6659): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 2188): client connected with version: 7571000
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300,
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6659): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6659): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6659): [1] 5.onFinished: Scheduling replication attempt 1.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  897): [PWL] Off : 680s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 27
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  897): waitForAlarm result :4
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6659): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6659): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6659): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  897): waitForAlarm result :4
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6659): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6659): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6659): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 28
,V/AlarmManager(  897): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/art     (  897): Explicit concurrent mark sweep GC freed 43632(2MB) AllocSpace objects, 62(1187KB) LOS objects, 30% free, 36MB/52MB, paused 1.794ms total 202.392ms
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6659): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6659): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6659): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 29
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6659): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6659): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6659): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,I/PowerManagerService(  897): [PWL] Off : 765s ago
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/TimaService(  897): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  897): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  897): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,V/AlarmManager(  897): waitForAlarm result :4
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6659): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6659): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6659): [1] 5.onFinished: Giving up after 6 failures.
,V/AlarmManager(  897): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 31
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): stay LED for fully charged
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 32
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,E/SMD     (  285): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,I/PowerManagerService(  897): [PWL] Off : 855s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 33
,E/SMD     (  285): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  897): stay LED for fully charged
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/GCM     ( 1693): Message class com.google.f.a.a.i
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GoogleURLConnFactory( 1693): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 34
,V/AlarmManager(  897): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED,
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 35
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  897): [PWL] Off : 950s ago
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 36
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 37
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 38
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 39
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  897): [PWL] Off : 1050s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1693): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6629): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at kff.l(PG:132)
E/HttpOperation( 6629): 	at dsf.a(PG:807)
E/HttpOperation( 6629): 	at fhk.a(PG:1126)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 8 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 10 more
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6629): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at kff.l(PG:132)
E/HttpOperation( 6629): 	at ieo.a(PG:43)
E/HttpOperation( 6629): 	at iep.a(PG:93)
E/HttpOperation( 6629): 	at fhn.a(PG:59)
E/HttpOperation( 6629): 	at lex.a(PG:85)
E/HttpOperation( 6629): 	at lex.b(PG:132)
E/HttpOperation( 6629): 	at fhk.a(PG:1146)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 12 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 14 more
,E/ExperimentLoader( 6629): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6629): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6629): 	at kfv.a(PG:65)
E/ExperimentLoader( 6629): 	at kff.u(PG:385)
E/ExperimentLoader( 6629): 	at kfb.a(PG:29)
E/ExperimentLoader( 6629): 	at kff.l(PG:132)
E/ExperimentLoader( 6629): 	at ieo.a(PG:43)
E/ExperimentLoader( 6629): 	at iep.a(PG:93)
E/ExperimentLoader( 6629): 	at fhn.a(PG:59)
E/ExperimentLoader( 6629): 	at lex.a(PG:85)
E/ExperimentLoader( 6629): 	at lex.b(PG:132)
E/ExperimentLoader( 6629): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6629): 	at fhk.a(PG:908)
E/ExperimentLoader( 6629): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6629): 	at ihi.a(PG:22)
E/ExperimentLoader( 6629): 	at kft.a(PG:91)
E/ExperimentLoader( 6629): 	at kfv.a(PG:62)
E/ExperimentLoader( 6629): 	... 12 more
E/ExperimentLoader( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6629): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6629): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6629): 	at ihi.a(PG:19)
E/ExperimentLoader( 6629): 	... 14 more
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6629): [getaccountstatus] Unexpected exception
E/HttpOperation( 6629): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6629): 	at kfv.a(PG:65)
E/HttpOperation( 6629): 	at kff.u(PG:385)
E/HttpOperation( 6629): 	at kfb.a(PG:29)
E/HttpOperation( 6629): 	at ixd.a(PG:248)
E/HttpOperation( 6629): 	at ixd.b(PG:206)
E/HttpOperation( 6629): 	at ixd.a(PG:175)
E/HttpOperation( 6629): 	at fig.a(PG:78)
E/HttpOperation( 6629): 	at lex.a(PG:85)
E/HttpOperation( 6629): 	at lex.b(PG:132)
E/HttpOperation( 6629): 	at fhk.a(PG:1146)
E/HttpOperation( 6629): 	at fhk.a(PG:908)
E/HttpOperation( 6629): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6629): 	at ihi.a(PG:22)
E/HttpOperation( 6629): 	at kft.a(PG:91)
E/HttpOperation( 6629): 	at kfv.a(PG:62)
E/HttpOperation( 6629): 	... 12 more
E/HttpOperation( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6629): 	at gde.c(Unknown Source)
E/HttpOperation( 6629): 	at gde.b(Unknown Source)
E/HttpOperation( 6629): 	at ihi.a(PG:19)
E/HttpOperation( 6629): 	... 14 more
,E/EsSyncAdapterService( 6629): Sync failure
E/EsSyncAdapterService( 6629): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6629): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6629): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6629): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6629): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6629): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6629): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6629): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6629): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6629): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6629): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6629): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6629): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6629): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6629): 	... 10 more
E/EsSyncAdapterService( 6629): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6629): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6629): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6629): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6629): 	... 12 more
E/EsSyncAdapterService( 6629): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6629): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6629): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6629): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6629): 	... 14 more
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1199309, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  897): mCursor = null
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/TimaService(  897): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  897): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  897): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  897): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  897): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  897): Updating Usage Statistics in DB @ 1450239356024
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
,W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  897): ::getAppControlDB: Exception to create DB
W/System.err(  897): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  897): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  897): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsage(  897): Done Updating Usage Statistics in DB @ 1450239356280
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,V/AlarmManager(  897): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7428): Starting books sync, d
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1693): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
D/SecContentProvider2(  897): mCursor = null
,D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7428): null auth token
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
,W/ApiaryClient( 7428): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6954107693164047503&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7428): null auth token
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Tagging socket 41 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
,W/ApiaryClient( 7428): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6954107693164047503&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  897): uri = 14 selection = getSealedState
,D/SecContentProvider2(  897): mCursor = null
D/SecContentProvider2(  897): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  897): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  897): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7428): Authentication error
E/BooksAccountManager( 7428): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7428): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7428): null auth token
,I/qtaguid ( 7428): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7428, getuid(): 10082
,I/qtaguid ( 7428): Untagging socket 34
,W/ApiaryClient( 7428): Error response from books API: {
W/ApiaryClient( 7428):  "error": {
W/ApiaryClient( 7428):   "errors": [
W/ApiaryClient( 7428):    {
W/ApiaryClient( 7428):     "domain": "global",
W/ApiaryClient( 7428):     "reason": "required",
W/ApiaryClient( 7428):     "message": "Login Required",
W/ApiaryClient( 7428):     "locationType": "header",
W/ApiaryClient( 7428):     "location": "Authorization"
W/ApiaryClient( 7428):    }
W/ApiaryClient( 7428):   ],
W/ApiaryClient( 7428):   "code": 401,
W/ApiaryClient( 7428):   "message": "Login Required"
W/ApiaryClient( 7428):  }
W/ApiaryClient( 7428): }
,W/ApiaryClient( 7428): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6954107693164047503&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7428): Headers suppressed
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/BooksSync( 7428): Soft error
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6954107693164047503&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7428): Headers suppressed
E/BooksSync( 7428): 
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7428): Sync error
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7428): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6954107693164047503&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7428): Headers suppressed
E/BooksSync( 7428): 
E/BooksSync( 7428): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7428): Finished books sync
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  897): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1208539, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  897): Explicit concurrent mark sweep GC freed 62682(4MB) AllocSpace objects, 120(2MB) LOS objects, 30% free, 36MB/52MB, paused 2.639ms total 180.211ms
D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  897): mCursor = null
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 41
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  897): waitForAlarm result :4
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 42
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  897): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  897): [PWL] Off : 1155s ago
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 43
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 44
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 45
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3234): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  897): !@Sync 46
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  897): [PWL] Off : 1265s ago
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 47
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  897): !@Sync 48
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,E/Watchdog(  897): !@Sync 49
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/TimaService(  897): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  897): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  897): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  897): !@Sync 50
,E/SMD     (  285): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  897): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/LightsService(  897): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  897): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  897): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  897): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  897): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  897): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  897): unregisterListener ::   
D/LightsService(  897): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  897): [PWL] Off : 1380s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  897): !@Sync 51
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 52
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  897): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  897): !@Sync 53
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  897): !@Sync 54
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  897): [PWL] Off : 1500s ago
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true,
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  897): !@Sync 55
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 56
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 280, PST = 288, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 57
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 280, PST = 287, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 280, PST = 286, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 280, PST = 285, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 58
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 280, PST = 284, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  897): [PWL] Off : 1625s ago
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 280, PST = 283, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 280, PST = 282, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 59
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  897): SIOP:: AP = 280, PST = 281, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 280, PST = 280, CUR = 300
,E/SMD     (  285): DCD ON
,D/NetworkStatsFactory(  897): UpdateStatsForKnox
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 280, PST = 280, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/TimaService(  897): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  897): TimaServiceHandler.handleMessage what =1
,D/TimaService(  897): TIMA: checkEvent, operation: 50000 subject: 10000
,E/Watchdog(  897): !@Sync 60
,E/SMD     (  285): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  897): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  897): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 281, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 282, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 283, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 61
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 284, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  897): stay LED for fully charged
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true,
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 285, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  897): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 290, PST = 286, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 62
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  897): SIOP:: AP = 280, PST = 286, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  897): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  897): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  897): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  897):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  897): Plugged
,I/MotionRecognitionService(  897): setPowerConnected  = true
,D/BatteryService(  897): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3234): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3234): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 280, PST = 286, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  897): [PWL] Off : 1755s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 280, PST = 286, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  897): !@Sync 63
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  897): SIOP:: AP = 280, PST = 286, CUR = 300
,E/SMD     (  285): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8949): 
D/AndroidRuntime( 8949): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8949): CheckJNI is OFF
D/AndroidRuntime( 8949): setted country_code = Germany
D/AndroidRuntime( 8949): setted countryiso_code = DE
D/AndroidRuntime( 8949): setted sales_code = DBT
D/AndroidRuntime( 8949): readGMSProperty: start
D/AndroidRuntime( 8949): readGMSProperty: already setted!!
D/AndroidRuntime( 8949): readGMSProperty: end
D/AndroidRuntime( 8949): addProductProperty: start
E/AffinityControl( 8949): AffinityControl: registerfunction enter
D/AndroidRuntime( 8949): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  897): START PACKAGE DELETE: observer{394870335}
D/PackageManager(  897): pkg{<packageName>}
D/PackageManager(  897): user{0}
D/PackageManager(  897): caller{2000}
D/PackageManager(  897): flags{3}
D/PersonaManagerService(  897): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  897): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  897): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  897): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  897): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  897): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  897): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  897): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  897): getApplicationUninstallationEnabled
D/ApplicationPolicy(  897): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  897): !@killApplicatoin: 10367, uninstall pkg
I/ActivityManager(  897): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
I/ActivityManager(  897): Killing 7507:com.test.thalitest/u0a367 (adj 0): stop com.test.thalitest
I/ActivityManager(  897): Killing 7972:com.samsung.android.sconnect/u0a138 (adj 15): empty for 1803s
I/ActivityManager(  897): Killing 7871:com.google.android.apps.magazines/u0a128 (adj 15): empty for 1803s
I/ActivityManager(  897): Killing 7855:com.android.chrome/u0a88 (adj 15): empty for 1803s
I/ActivityManager(  897): Killing 7836:com.sec.chaton/u0a86 (adj 15): empty for 1803s
I/ActivityManager(  897): Killing 7821:com.sec.knox.bridge/1000 (adj 15): empty for 1803s
I/ActivityManager(  897): Killing 7337:com.sec.android.widgetapp.ap.hero.accuweather/u0a71 (adj 15): empty for 1803s
I/ActivityManager(  897): Killing 7797:com.osp.app.signin/u0a45 (adj 15): empty for 1803s
I/ActivityManager(  897): Killing 7748:com.policydm/1000 (adj 15): empty for 1803s
I/ActivityManager(  897): Killing 7733:com.sec.android.soagent/u0a37 (adj 15): empty for 1803s
I/ActivityManager(  897): Killing 7718:com.samsung.klmsagent/u0a19 (adj 15): empty for 1803s
I/ActivityManager(  897): Killing 7699:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1803s
I/ActivityManager(  897): Killing 7678:com.sec.android.diagmonagent/1000 (adj 15): empty for 1803s
I/ActivityManager(  897): Killing 7656:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1803s
I/ActivityManager(  897): Killing 5361:com.google.android.music:main/u0a126 (adj 15): empty for 1803s
I/ActivityManager(  897): Killing 7640:com.sec.pcw.device/1000 (adj 15): empty for 1803s
I/ActivityManager(  897): Killing 7158:com.samsung.dcm:DCMService/u0a4 (adj 15): empty for 1803s
I/ActivityManager(  897): Killing 8016:com.sec.android.provider.badge/u0a78 (adj 15): empty for 1804s
I/ActivityManager(  897): Killing 7268:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): empty for 1811s
I/ActivityManager(  897): Killing 7403:com.sec.android.app.camera/u0a154 (adj 15): empty for 1830s
I/ActivityManager(  897): Killing 7385:com.sec.android.GeoLookout/u0a113 (adj 15): empty for 1830s
I/ActivityManager(  897): Killing 7369:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): empty for 1831s
I/ActivityManager(  897): Killing 7350:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): empty for 1831s
I/ActivityManager(  897): Killing 5691:com.android.mms/u0a50 (adj 15): empty for 1831s
I/ActivityManager(  897): Killing 6014:com.sec.android.gallery3d/u0a48 (adj 15): empty for 1831s
I/ActivityManager(  897): Killing 4880:com.android.defcontainer/u0a5 (adj 15): empty for 1839s
I/ActivityManager(  897): Killing 4738:com.google.android.gms.wearable/u0a12 (adj 15): empty for 1841s
I/ActivityManager(  897): Killing 7194:com.sec.android.app.music:service/u0a44 (adj 15): empty for 1846s
I/ActivityManager(  897): Killing 6247:com.google.android.gm/u0a114 (adj 15): empty for 1846s
I/ActivityManager(  897): Killing 6711:com.google.android.gms:car/u0a12 (adj 15): empty for 1846s
I/ActivityManager(  897):   Force finishing activity ActivityRecord{100cbbd5 u0 com.test.thalitest/.MainActivity t11}
D/FocusedStackFrame(  897): Set to : 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/ProcessStatsService(  897): Prepared write state in 8ms
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/WifiService(  897): Client connection lost with reason: 4
I/ProcessStatsService(  897): Pruning old procstats: /data/system/procstats/state-2015-12-15-18-03-13.bin
W/PackageSettings(  897): Skipping PackageSetting{2e0bc0b8 com.example.hello/10375} due to missing metadata
D/ConnectivityService(  897): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/CountryDetector(  897): No listener is left
I/ActivityManager(  897): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
I/art     ( 4472): Explicit concurrent mark sweep GC freed 4028(225KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 321us total 19.284ms
I/art     ( 1575): Explicit concurrent mark sweep GC freed 7911(578KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/27MB, paused 389us total 18.628ms
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager( 1497): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
W/ResourcesManager( 1497): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1497): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
E/SamsungIME( 1868): mOCRHelper is null
D/ResourcesManager( 1497): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
W/ResourcesManager( 1497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1497): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
W/BroadcastQueue(  897): Failure sending broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/BroadcastQueue(  897): android.os.RemoteException: app.thread must not be null
W/BroadcastQueue(  897): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:484)
W/BroadcastQueue(  897): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:600)
W/BroadcastQueue(  897): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:652)
W/BroadcastQueue(  897): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:180)
W/BroadcastQueue(  897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  897): 	at android.os.Looper.loop(Looper.java:145)
W/BroadcastQueue(  897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue(  897): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
W/GeofencerStateMachine( 2188): Ignoring removeGeofence because network location is disabled.
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8979): MountEmulatedStorage()
E/Zygote  ( 8979): v2
I/libpersona( 8979): KNOX_SDCARD checking this for 10019
I/libpersona( 8979): KNOX_SDCARD not a persona
I/ActivityManager(  897): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8979 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 8979): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/InputReader(  897): Reconfiguring input devices.  changes=0x00000010
I/SELinux ( 8979): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8979): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8979): TimaSignature is unavailable
D/ActivityThread( 8979): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/art     (  897): Explicit concurrent mark sweep GC freed 50500(5MB) AllocSpace objects, 211(3MB) LOS objects, 30% free, 36MB/52MB, paused 2.027ms total 170.673ms
I/art     (  897): WaitForGcToComplete blocked for 80.655ms for cause Explicit
D/ResourcesManager(  897): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SurfaceWidgetView( 1497): destroyHardwareResources():240378142
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
V/WindowOrientationListener(  897): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  897): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  897): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  897): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  897): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/Launcher( 1497): onRestart, Launcher: 436157158
D/Launcher( 1497): onStart, Launcher: 436157158
D/Launcher.HomeView( 1497): onStart
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager( 8979): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2164): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2164): [237392/6] SurfaceWidget drawing first frame
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBarManagerService(  897): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/StatusBarManagerService(  897): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/SecContentProvider2(  897): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  897): mCursor = null
I/KLMS-2.4.503: ( 8979): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
I/KLMS-2.4.503: ( 8979): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1450240052713
D/RegisteredServicesCache( 1467): empty dynamic service
I/KLMS-2.4.503: ( 8979): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.503: ( 8979): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/InputMethodManagerService(  897): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/talkback/talkback.apk
W/ContextImpl(  897): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService(  897): Got RemoteException sending setActive(false) notification to pid 7507 uid 10367
D/EnterpriseDeviceManagerService(  897): Package has changed for user 0
D/EnterpriseDeviceManagerService(  897): Admin package name: com.google.android.gms
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Books/Books.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 9000): MountEmulatedStorage()
E/Zygote  ( 9000): v2
I/libpersona( 9000): KNOX_SDCARD checking this for 10104
I/libpersona( 9000): KNOX_SDCARD not a persona
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
I/ActivityManager(  897): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=9000 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  897): Killing 7993:com.android.email/u0a163 (adj 15): empty for 1804s
I/Timeline(  897): Timeline: Activity_windows_visible id: ActivityRecord{2dce69e4 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:1908743
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
I/SELinux ( 9000): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 9000): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/art     (  897): Explicit concurrent mark sweep GC freed 12775(638KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 2.283ms total 222.772ms
E/SELinux ( 9000): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/TimaKeyStoreProvider( 9000): TimaSignature is unavailable
D/ActivityThread( 9000): Added TimaKeyStore provider
D/ResourcesManager( 9000): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/elm:14451( 9000): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/elm:14451( 9000): ELMEngine.ELMEngine( context ).
D/elm:14451( 9000): MDMBridge.setEnterpriseBridge()
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/elm:14451( 9000): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
D/elm:14451( 9000): ElmAgentService : onCreate()
D/elm:14451( 9000): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/elm:14451( 9000): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 9000): MDMBridge.getInstance()
D/elm:14451( 9000): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 9016): MountEmulatedStorage()
E/Zygote  ( 9016): v2
I/libpersona( 9016): KNOX_SDCARD checking this for 10017
D/elm:14451( 9000): MDMBridge.getAllLicenseInfoFromSDK()
I/libpersona( 9016): KNOX_SDCARD not a persona
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
I/ActivityManager(  897): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=9016 uid=10017 gids={50017, 9997} abi=armeabi-v7a
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Videos/Videos.apk
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/SELinux ( 9016): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 9016): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 9016): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 9016): TimaSignature is unavailable
D/ActivityThread( 9016): Added TimaKeyStore provider
D/elm:14451( 9000): ElmAgentService : onDestroy().
I/ActivityManager(  897): Killing 7571:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1804s
D/ResourcesManager(  897): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager( 9016): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/RCPManagerService(  897): PackageReceiver onReceive()
I/HarmonyEASService(  897): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/KnoxMUMContainerPolicy(  897): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  897): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  897): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  897): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  897): uID is 10367
V/EnterpriseBillingPolicy(  897): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  897): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  897): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  897): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  897): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  897): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  897): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  897): removeObsoleteFile: deleting file=11_task.xml
D/TaskPersister(  897): removeObsoleteFile: deleting file=11_task_thumbnail.png
D/ResourcesManager(  897): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/com.sec.android.service.health.upgrade.UninstallReceiver( 9016): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 9016): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 9016): onReceive() : package name is not s health. Return !!!
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager(  897): delete codoeFile: 
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
D/PackageManager(  897): result of delete: 1{394870335}
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Drive/Drive.apk
E/Zygote  ( 9032): MountEmulatedStorage()
E/Zygote  ( 9032): v2
I/libpersona( 9032): KNOX_SDCARD checking this for 1000
I/libpersona( 9032): KNOX_SDCARD not a persona
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/ActivityManager(  897): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=9032 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/AndroidRuntime( 8949): Shutting down VM
I/ActivityManager(  897): Killing 8034:com.samsung.android.service.travel/u0a178 (adj 15): empty for 1804s
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
I/SELinux ( 9032): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 9032): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 9032): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/TimaKeyStoreProvider( 9032): TimaSignature is unavailable
W/ResourcesManager(  897): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  897): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  897): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityThread( 9032): Added TimaKeyStore provider
D/ResourcesManager( 9032): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
W/Resources(  897): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  897): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
I/PCWCLIENTTRACE_LOG( 9032): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 9032): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 9032): new DMDBOpenHelper instance
I/PCWCLIENTTRACE_PushUtil( 9032): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 9032): sales region : global
I/PCWCLIENTTRACE_PushUtil( 9032): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 9032): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  897): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  897): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
E/Zygote  ( 9047): MountEmulatedStorage()
E/Zygote  ( 9047): v2
I/libpersona( 9047): KNOX_SDCARD checking this for 10034
I/libpersona( 9047): KNOX_SDCARD not a persona
I/SELinux ( 9047): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 9047): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 9047): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  897): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk

```
