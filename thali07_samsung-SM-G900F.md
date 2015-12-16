#### Test 50650278e989a4f_thali07_samsung-SM-G900F Logs


```
--------- beginning of main,
E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
--------- beginning of system
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7416): null auth token
I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
I/qtaguid ( 7416): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
E/SMD     (  285): DCD ON
I/qtaguid ( 7416): Untagging socket 34
W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
W/ApiaryClient( 7416): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1488019987285089289&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
D/AndroidRuntime( 7459): 
D/AndroidRuntime( 7459): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7459): CheckJNI is OFF
D/AndroidRuntime( 7459): setted country_code = Germany
D/AndroidRuntime( 7459): setted countryiso_code = DE
D/AndroidRuntime( 7459): setted sales_code = DBT
D/AndroidRuntime( 7459): readGMSProperty: start
D/AndroidRuntime( 7459): readGMSProperty: already setted!!
D/AndroidRuntime( 7459): readGMSProperty: end
D/AndroidRuntime( 7459): addProductProperty: start
E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
E/AffinityControl( 7459): AffinityControl: registerfunction enter
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
D/AndroidRuntime( 7459): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  834): inState():  stateMachine is null !!
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  834): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  834): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  834): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 834  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  834): mDVFSHelper.acquire()
D/FocusedStackFrame(  834): Set to : 0
D/Launcher.HomeView( 1489): onPause
D/Launcher( 1489): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 7459): Shutting down VM
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/TaskCloserActivity( 7245): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/Zygote  ( 7489): MountEmulatedStorage()
E/Zygote  ( 7489): v2
I/libpersona( 7489): KNOX_SDCARD checking this for 10367
I/SurfaceFlinger(  248): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
I/libpersona( 7489): KNOX_SDCARD not a persona
I/ActivityManager(  834): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7489 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SELinux ( 7489): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7489): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7489): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBarManagerService(  834): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/MicrophoneInputStream( 1585): mic_close gfk@13b8a0b3
V/AudioPolicyManager(  291): stopInput() input 29
V/AudioPolicyManager(  291): releaseInput() 29
V/AudioPolicyManager(  291): closeInput(29)
I/HotwordRecognitionRnr( 1585): Stopping hotword detection.
I/HotwordRecognitionRnr( 1585): Hotword detection finished
D/TimaKeyStoreProvider( 7489): TimaSignature is unavailable
D/ActivityThread( 7489): Added TimaKeyStore provider
V/audio_hw_primary(  291): in_standby: enter
V/WindowOrientationListener(  834): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  834): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  834): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  834): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  834): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  834): Display changed displayId=0
D/Launcher.HomeView( 1489): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2264): [237392/6] Surface widget pause on instance = 1
E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
D/accuweather( 2264): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2264): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2264): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2264): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SurfaceWidgetView( 1489): destroyHardwareResources():884048749
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBarManagerService(  834): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/audio_hw_primary(  291): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  291): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  291): disable_audio_route: reset mixer path: audio-record
D/audio_route(  291): ++++ audio_route_update_mixer ==============
D/audio_route(  291): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  291): Setting mixer control: value: 0
D/audio_route(  291): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  291): disable_audio_route: exit
V/audio_hw_primary(  291): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  291): ++++ audio_route_update_mixer ==============
D/audio_route(  291): Setting mixer control: DEC2 Volume
D/audio_route(  291): Setting mixer control: value: 0
D/audio_route(  291): Setting mixer control: SLIM TX7 MUX, value: 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/audio_route(  291): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  291): Setting mixer control: value: 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/audio_route(  291): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  291): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  291): stop_input_stream: exit: status(0)
V/audio_hw_primary(  291): in_standby: exit:  status(0)
V/audio_hw_primary(  291): adev_close_input_stream
V/audio_hw_primary(  291): in_standby: enter
V/audio_hw_primary(  291): in_standby: exit:  status(0)
E/audio_hw_primary(  291): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  291): releaseInput() exit
D/accuweather( 2264): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2264): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7489): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
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
D/Launcher( 1489): onTrimMemory. Level: 20
D/SurfaceWidgetView( 1489): destroyHardwareResources():884048749
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
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/art     (  834): Explicit concurrent mark sweep GC freed 66479(3MB) AllocSpace objects, 16(386KB) LOS objects, 30% free, 36MB/52MB, paused 1.334ms total 123.205ms
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/WebViewFactory( 7489): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7489): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
I/LibraryLoader( 7489): Loading: webviewchromium
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/LibraryLoader( 7489): Time to load native libraries: 2 ms (timestamps 5438-5440)
I/LibraryLoader( 7489): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/WebViewChromiumFactoryProvider( 7489): Binding Chromium to main looper Looper (main, tid 1) {13cf12c1}
I/LibraryLoader( 7489): Expected native library version number "",actual native library version number ""
I/chromium( 7489): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7489): Initializing chromium process, renderers=0
W/art     ( 7489): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7489): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7489): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7489): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/Adreno-EGL( 7489): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7489): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7489): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7489): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7489): Remote Branch: 
I/Adreno-EGL( 7489): Local Patches: 
I/Adreno-EGL( 7489): Reconstruct Branch: 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/chromium( 7489): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/chromium( 7489): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7489): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7489): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SystemWebViewEngine( 7489): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/art     ( 7489): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7489): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/Activity( 7489): performCreate Call secproduct feature valuefalse
D/Activity( 7489): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/OpenGLRenderer( 7489): Render dirty regions requested: true
D/ActivityManager(  834): post active user change for 0
D/KnoxTimeoutHandler(  834): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  834): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  248): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
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
I/OpenGLRenderer( 7489): Initialized EGL, version 1.4
I/OpenGLRenderer( 7489): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7489): Enabling debug mode 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/InputMethodManagerService(  834): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1169): value : false
W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/Timeline( 7489): Timeline: Activity_idle id: android.os.BinderProxy@1adedad8 time:95730
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/ActivityManager(  834): Displayed com.test.thalitest/.MainActivity: +571ms
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
I/SurfaceFlinger(  248): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  248): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7416): null auth token
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_out.png
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/JsMessageQueue( 7489): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/qtaguid ( 7416): Untagging socket 34
W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
W/ApiaryClient( 7416): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1488019987285089289&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/chromium( 7489): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7489): 
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
I/SurfaceFlinger(  248): id=14 Removed Starting com.test.thalitest (7/8)
I/SurfaceFlinger(  248): id=14 Removed Starting com.test.thalitest (-2/8)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/jxcore_app_log( 7489): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358154752
D/JX-Cordova( 7489): jxcore cordova android initializing
E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  834): CMD_RSSI_POLL : out!
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/CustomFrequencyManagerService(  834): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 834  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  834): mDVFSHelper.release()
I/Timeline(  834): Timeline: Activity_windows_visible id: ActivityRecord{37aeb80 u0 com.test.thalitest/.MainActivity t11} time:96063
D/CustomFrequencyManagerService(  834): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 834  pkgName : ACTIVITY_RESUME_BOOSTER@10
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
E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  834): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 834  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/BooksSync( 7416): Soft error,
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1488019987285089289&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7416): Headers suppressed
E/BooksSync( 7416): 
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7416): Sync error
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1488019987285089289&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7416): Headers suppressed
E/BooksSync( 7416): 
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7416): Finished books sync
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  834): Killing 6740:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,D/SyncManager(  834): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 66815, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  834): mCursor = null
,W/libprocessgroup(  834): failed to open /acct/uid_10015/pid_6740/cgroup.procs: No such file or directory
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  834): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1169 (0x0)
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,W/jxcore-log( 7489): Initializing JXcore engine
,W/jxcore-log( 7489): JXcore engine is ready
,W/jxcore-log( 7489): Starting JXcore engine
,E/auditd  ( 2102): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  834): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  834): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  834): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7549 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 7549): MountEmulatedStorage()
,E/Zygote  ( 7549): v2
I/libpersona( 7549): KNOX_SDCARD checking this for 1000
I/libpersona( 7549): KNOX_SDCARD not a persona
,I/SELinux ( 7549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7549): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,W/jxcore-log( 7489): Platform android
W/jxcore-log( 7489): 
,W/jxcore-log( 7489): Process ARCH arm
W/jxcore-log( 7489): 
,D/TimaKeyStoreProvider( 7549): TimaSignature is unavailable
,D/ActivityThread( 7549): Added TimaKeyStore provider
,E/SMD     (  285): DCD ON
,D/ResourcesManager( 7549): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7549):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
D/SecurityLogAgent( 7549):  SeDenialReceiver : File path = null
,I/ActivityManager(  834): Killing 6761:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,W/libprocessgroup(  834): failed to open /acct/uid_10016/pid_6761/cgroup.procs: No such file or directory
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/GAV2    ( 7416): Thread[GAThread,5,main]: No campaign data found.
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  834): SIOP:: AP = 380, PST = 430, CUR = 300
,I/jxcore-log( 7489): JXcore Cordova bridge is ready!
I/jxcore-log( 7489): 
W/jxcore-log( 7489): JXcore engine is started
,E/Adreno-ES20( 7489): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 7489): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : out!
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7489): Toggling radios to true
I/jxcore-log( 7489): 
,D/BluetoothAdapter( 7489): enable()
,D/BluetoothAdapter( 7489): enable(): BT is already enabled..!
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/WifiService(  834): New client listening to asynchronous messages
,I/WifiManager( 7489): packageName : com.test.thalitest
,D/SecContentProvider(  834): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  834): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  834): mCursor = null
,D/WifiService(  834): setWifiEnabled: true pid=7489, uid=10367
E/WifiService(  834): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  834): Permission Denial: getCurrentUser() from pid=7489, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  834): Failed getting userId using ActivityManagerNative
W/WifiService(  834): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7489, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  834): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  834): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  834): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  834): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  834): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  834): name = wifi_on
,I/WifiService(  834): disconnect: pid=7489, uid=10367
,I/wpa_supplicant( 1273): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7489): Radios toggled
I/jxcore-log( 7489): 
,I/wpa_supplicant( 1273): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1273): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1273): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  834): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1273): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1273): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1273): Disconnected - do not scan
I/wpa_supplicant( 1273): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  834): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  834): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  834): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  834): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log( 7489): Got Device Bluetooth address: B0:C5:59:3F:75:69
I/jxcore-log( 7489): 
,I/jxcore-log( 7489): Perf Test app loaded loaded
I/jxcore-log( 7489): 
,E/WifiStateMachine(  834): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,I/jxcore-log( 7489): check test folder
I/jxcore-log( 7489): 
D/WifiP2pService(  834): InactiveState{ what=143375 }
D/WifiP2pService(  834): P2pEnabledState{ what=143375 }
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/AlarmManager(  834): waitForAlarm result :4
,I/jxcore-log( 7489): found test : ./testFindPeers.js
I/jxcore-log( 7489): 
,I/jxcore-log( 7489): found test : ./testSendData.js
I/jxcore-log( 7489): 
,E/WifiStateMachine(  834): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  834): updateNetworkInfo()
,D/ConnectivityService(  834): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  834): updateNetworkInfo()
,D/ConnectivityService(  834): ignoring duplicate network state non-change
D/ConnectivityService(  834): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiConfigStore(  834): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller(  834): evaluateTrafficStatsPolling
,V/NativeCrypto( 1718): Read error: ssl=0xae668600: I/O error during system call, Connection timed out
,I/CLocInfoService(  834): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  834): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1273): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1273): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1273): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1273): First Scan Start
,I/wpa_supplicant( 1273): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  834): ConnectModeState: Network connection lost 
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/WifiStateMachine(  834): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  834): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,V/NativeCrypto( 1718): SSL shutdown failed: ssl=0xae668600: I/O error during system call, Broken pipe
,D/WifiP2pService(  834): InactiveState{ what=143375 }
,D/WifiP2pService(  834): P2pEnabledState{ what=143375 }
,I/Hs20UtilService( 1301): Starting #6
,I/Hs20UtilService( 1301): Message received 5007
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  834): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  834): ValidatedState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  834): DefaultState{ when=-4ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  834): Forcing reevaluation
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1301): MountReceiver.onReceive - Set preference state off
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  834): EvaluatingState{ when=-5ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  834): Validated
,V/NearbySettings( 1301): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,D/ConnectivityService(  834): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  834): calling update connectivity
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,E/WifiStateMachine(  834): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  834): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  834): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  834): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  834): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  834): Not allowed due to - mEnabled false
D/WifiStateMachine(  834): updateConfiguredNetworkExpiration - currTime: 1450233031556
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  834): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  834): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  834): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  834): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  834): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  834): Disconnected - quitting
D/TelephonyNetworkFactory( 1474): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WifiTrafficPoller(  834): evaluateTrafficStatsPolling
,D/WifiStateMachine(  834): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,E/WifiStateMachine(  834): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  834): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiNetworkAgent(  834): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  834): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  834): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
I/CLocInfoService(  834): External Intent Received android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  834): setDetailed state send new extra info"NG700"
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/SecContentProvider2(  834): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  834): mCursor = null
,D/ConnectivityService(  834): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  834): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  834): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  834): getSBEnabled() enabled =false
D/SmartBondingService(  834): getSBEnabled() enabled =false
D/SmartBondingService(  834): getSBEnabled() enabled =false
,V/NetworkStats(  834): updateIfacesLocked()
,V/NetworkStats(  834): performPollLocked(flags=0x1)
D/NtpTrustedTime(  834): currentTimeMillis() cache hit
,D/SmartBondingService(  834): getNetworkEnabled : wifi : true mobile : true
,D/NetworkStatsFactory(  834): UpdateStatsForKnox
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  834): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
,E/ConnectivityService(  834): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NtpTrustedTime(  834): currentTimeMillis() cache hit
D/NtpTrustedTime(  834): currentTimeMillis() cache hit
V/NetworkStats(  834): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  834): currentTimeMillis() cache hit
,V/NetworkStats(  834): performPollLocked() took 7ms
,D/NtpTrustedTime(  834): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/SecContentProvider2(  834): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  834): mCursor = null
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/NtpTrustedTime(  834): currentTimeMillis() cache hit
D/NtpTrustedTime(  834): currentTimeMillis() cache hit
,I/Hs20UtilService( 1301): Starting #7
,I/Hs20UtilService( 1301): Message received 5007
D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1301): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,I/Choreographer( 7489): Skipped 80 frames!  The application may be doing too much work on its main thread.
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,I/chromium( 7489): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 7489): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6669): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6669): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6669): [1] 5.onFinished: Scheduling replication attempt 2.
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  834): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  834): updateDataUsageMap
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/accuweather( 2264): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  834): MasterInitialState.processMessage what=3
,D/SmartBondingService(  834): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  834): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  834): getSBEnabled() enabled =false
,D/SmartBondingService(  834): getSBEnabled() enabled =false
D/SmartBondingService(  834): getSBEnabled() enabled =false
,I/CLocInfoService(  834): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  834): CLoinfo wifi false
,D/SmartBondingService(  834): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/SLocation(  834): No Active Data Connection
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 6777): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6777): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6777): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6777): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6777): noConnectivity : true
,I/DBG_DM  ( 3713): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3713): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7620): MountEmulatedStorage()
E/Zygote  ( 7620): v2
I/libpersona( 7620): KNOX_SDCARD checking this for 10126
I/libpersona( 7620): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7620 uid=10126 gids={50126, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7620): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7620): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7620): TimaSignature is unavailable
,D/ActivityThread( 7620): Added TimaKeyStore provider
,D/ResourcesManager( 7620): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/MusicStore( 7620): Database version: 104
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/ResourcesManager( 7620): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7620): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7620): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7620): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7620): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7620): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2fee1903: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7620): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7620): GMSCore installation verified
,I/ConfigStore( 7620): Config Database version: 1
,I/wpa_supplicant( 1273): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 1273): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1273): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1273): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  834): [1,450,233,032,590 ms] noteScanEnd no scan source
,E/WifiStateMachine(  834): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@24b4d811 sup_state=SCANNING debouncing=false
,I/CLocInfoService(  834): External Intent Received android.net.wifi.SCAN_RESULTS
,E/WifiStateMachine(  834): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  834): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  834): setDetailed state send new extra info0x
,D/SecContentProvider2(  834): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  834): mCursor = null
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7620): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7620): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7620): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter(  834): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  834): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  291): getOutputsForDevice device 0002 -> 0002
I/AudioService(  834): getStreamVolume 3 index 70
,I/MediaRouter( 7620): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
I/wpa_supplicant( 1273): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1273): Associated with C0.AA.48
E/WifiStateMachine(  834): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  834): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2(  834): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  834): mCursor = null
,E/Zygote  ( 7657): MountEmulatedStorage()
,E/Zygote  ( 7657): v2
I/libpersona( 7657): KNOX_SDCARD checking this for 10002
I/libpersona( 7657): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7657 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7657): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/wpa_supplicant( 1273): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
I/SELinux ( 7657): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7657): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  834): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  834): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  834): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  834): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  834): mCursor = null
,D/WifiDisplayAdapter(  834): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7620): type=WIFI subType= reason=null isConnected=false
,I/wpa_supplicant( 1273): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1273): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1273): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1273): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1273): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  834): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  834): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 1273): Blacklist: Clear (temp) 
I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  834): Network connection established
,D/WifiNative-HAL(  834): callSECApiVoid - ID [50]
,E/WifiStateMachine(  834): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  834): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService(  834): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  834): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  834): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService(  834): Got NetworkAgent Messenger
E/ConnectivityService(  834): updateNetworkInfo()
D/ConnectivityService(  834): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  834): NetworkAgent connected
E/WifiStateMachine(  834): L2ConnectedState "NG700" nid=0
,E/WifiConfigStore(  834): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/CLocInfoService(  834): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  834): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,D/TimaKeyStoreProvider( 7657): TimaSignature is unavailable
,D/ActivityThread( 7657): Added TimaKeyStore provider
,E/WifiStateMachine(  834): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  834): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  834): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  277): Setting iface cfg
E/WifiStateMachine(  834): Start Dhcp Watchdog 2
,D/SecContentProvider2(  834): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  834): mCursor = null
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore in!
I/ActivityManager(  834): Killing 6541:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,E/WifiStateMachine(  834): calculateWifiScore() report new score 60
I/WifiStateMachine(  834): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  834): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  834): CMD_RSSI_POLL : out!
,D/ConnectivityService(  834): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  834): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  834): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  834): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/ResourcesManager( 7657): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,W/libprocessgroup(  834): failed to open /acct/uid_10034/pid_6541/cgroup.procs: No such file or directory
,I/ActivityManager(  834): Killing 4759:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7677): MountEmulatedStorage()
I/libpersona( 7677): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7677): v2
I/libpersona( 7677): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7677 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/WifiStateMachine(  834): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  834): do suspend false
,D/SecContentProvider2(  834): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  834): mCursor = null
,D/WifiP2pService(  834): InactiveState{ what=143375 }
D/WifiP2pService(  834): P2pEnabledState{ what=143375 }
,I/SELinux ( 7677): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7677): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7677): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7677): TimaSignature is unavailable
,D/ActivityThread( 7677): Added TimaKeyStore provider
,D/ResourcesManager( 7677): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  834): failed to open /acct/uid_10035/pid_4759/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7677): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7677): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/DIAGMON_AGENT( 7677): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7677): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7677): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7677): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/dhcpcd  ( 7693): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7693): version 5.5.6 starting
,E/dhcpcd  ( 7693): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7698): MountEmulatedStorage()
E/Zygote  ( 7698): v2
I/libpersona( 7698): KNOX_SDCARD checking this for 10011
I/libpersona( 7698): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7698 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7698): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7698): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7698): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 7693): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7693): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7693): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7693): bssid match
,I/dhcpcd  ( 7693): wlan0: rebinding lease of 192.168.1.135
,D/TimaKeyStoreProvider( 7698): TimaSignature is unavailable
,D/ActivityThread( 7698): Added TimaKeyStore provider
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/ResourcesManager( 7698): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  834): Killing 6794:com.policydm/1000 (adj 15): bgCount ##41
,I/FOTA_Client( 7698): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7698): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7698): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7698): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7698): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  834): failed to open /acct/uid_1000/pid_6794/cgroup.procs: No such file or directory
,E/Zygote  ( 7716): MountEmulatedStorage()
,E/Zygote  ( 7716): v2
I/libpersona( 7716): KNOX_SDCARD checking this for 10019
I/libpersona( 7716): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7716 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  834): Killing 5298:com.sec.spp.push/u0a38 (adj 15): bgCount ##41
,I/SELinux ( 7716): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7716): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7716): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PowerManagerService(  834): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  834): [s] DisplayPowerCallbacks : onStateChanged()
,W/libprocessgroup(  834): failed to open /acct/uid_10038/pid_5298/cgroup.procs: No such file or directory
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
D/lights  (  834): lcd : 1 +
,D/lights  (  834): lcd : 1 -
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
D/TimaKeyStoreProvider( 7716): TimaSignature is unavailable
,D/ActivityThread( 7716): Added TimaKeyStore provider
,D/ResourcesManager( 7716): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7716): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7716): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450233033335
,I/KLMS-2.4.503: ( 7716): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7716): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7716): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  834): Killing 6037:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7731): MountEmulatedStorage()
I/libpersona( 7731): KNOX_SDCARD checking this for 10037
E/Zygote  ( 7731): v2
I/libpersona( 7731): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7731 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7731): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7731): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7731): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  315): Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 708us total 17.330ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 8.662ms
,D/TimaKeyStoreProvider( 7731): TimaSignature is unavailable
,D/ActivityThread( 7731): Added TimaKeyStore provider
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 8.803ms
,W/libprocessgroup(  834): failed to open /acct/uid_10042/pid_6037/cgroup.procs: No such file or directory
,D/ResourcesManager( 7731): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7731): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7750): MountEmulatedStorage()
E/Zygote  ( 7750): v2
I/libpersona( 7750): KNOX_SDCARD checking this for 1000
I/libpersona( 7750): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7750 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  834): Killing 6815:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,I/SELinux ( 7750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7750): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  834): failed to open /acct/uid_10045/pid_6815/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7750): TimaSignature is unavailable
,D/ActivityThread( 7750): Added TimaKeyStore provider
,D/ResourcesManager( 7750): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7770): MountEmulatedStorage()
E/Zygote  ( 7770): v2
I/libpersona( 7770): KNOX_SDCARD checking this for 10038
,I/libpersona( 7770): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7770 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  834): Killing 6864:com.sec.android.provider.badge/u0a78 (adj 15): bgCount ##41
,I/SELinux ( 7770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7770): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 7693): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,W/libprocessgroup(  834): failed to open /acct/uid_10078/pid_6864/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7770): TimaSignature is unavailable
,D/ActivityThread( 7770): Added TimaKeyStore provider
,D/ResourcesManager( 7770): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,I/dhcpcd  ( 7693): wlan0: leased 192.168.1.135 for 86400 seconds
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  834): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  834): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  834): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/SPPClientService( 7770): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7770): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7770): PushLog.txt file is not deleted.
,D/SPPClientService( 7770): PushLog.txt file is not deleted.
D/SPPClientService( 7770): ============PushLog. stop!
,E/SPPClientService( 7770): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7795): MountEmulatedStorage()
,E/Zygote  ( 7795): v2
I/libpersona( 7795): KNOX_SDCARD checking this for 10045
I/libpersona( 7795): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7795 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7795): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7795): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7795): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 7770): [[SystemStateMonitorService]] No Active Internet
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,D/TimaKeyStoreProvider( 7795): TimaSignature is unavailable
,D/ActivityThread( 7795): Added TimaKeyStore provider
,I/ActivityManager(  834): Killing 6881:com.wsomacp/u0a25 (adj 15): bgCount ##41
,D/ResourcesManager( 7795): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/SA      ( 7795): [SSP] onCreated
,W/libprocessgroup(  834): failed to open /acct/uid_10025/pid_6881/cgroup.procs: No such file or directory
,I/SA      ( 7795): [TPM] There is no property file
,I/SA      ( 7795): [SCU] isHaveSA() - false
,I/SA      ( 7795): [TPM] getModelProperty : null
,I/SA      ( 7795): [TPM] getCSCProperty : null
,I/SA      ( 7795): [DM] init START
,I/SA      ( 7795): [DM] This device is not a Vodafone
,W/ResourceType( 7795): Failure getting entry for 0x7f06000f (t=5 e=15) (error -75)
,W/ResourceType( 7795): Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
W/ResourceType( 7795): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 7795): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 7795): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7795): Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
W/ResourceType( 7795): Failure getting entry for 0x7f060013 (t=5 e=19) (error -75)
,W/ResourceType( 7795): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7795): Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
W/ResourceType( 7795): Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
W/ResourceType( 7795): Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
,W/ResourceType( 7795): Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
W/ResourceType( 7795): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 7795): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 7795): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 7795): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 7795): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 7795): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 7795): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 7795): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,I/SA      ( 7795): [SCU] isHaveSA() - false
,I/SA      ( 7795): support phone number id : false
I/SA      ( 7795): [DM] init END
,I/SA      ( 7795): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7795): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 7795): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 7795): [SLFUCHKMGR] constructor called
,I/SA      ( 7795): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7795): [OR] == isSIMCardReady false ==
I/SA      ( 7795): [SCU] == networkStateCheck == false
,I/SA      ( 7795): [OR] onReceive END
,I/ActivityManager(  834): Killing 6897:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,D/accuweather( 7317): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7317): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7317): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7317): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7317): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7317): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7317): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7317): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/libprocessgroup(  834): failed to open /acct/uid_10051/pid_6897/cgroup.procs: No such file or directory
,D/accuweather( 7317): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7317): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7829): MountEmulatedStorage()
,E/Zygote  ( 7829): v2
I/libpersona( 7829): KNOX_SDCARD checking this for 1000
I/libpersona( 7829): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7829 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7829): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7829): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7829): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  834): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,D/WifiP2pService(  834): InactiveState{ what=143375 }
D/WifiP2pService(  834): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  834): WifiStateMachine DHCP successful
,E/WifiStateMachine(  834): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  834): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  834): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  834): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  834): Not connected state, yet.
,E/WifiStateMachine(  834): VerifyingLinkState enter
,D/WifiStateMachine(  834): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  834): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  834): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  834): callSECApiInt - ID [210]
,E/WifiStateMachine(  834): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,D/TimaKeyStoreProvider( 7829): TimaSignature is unavailable
,E/ConnectivityService(  834): updateNetworkInfo()
,D/ActivityThread( 7829): Added TimaKeyStore provider
D/ConnectivityService(  834): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  834): Adding iface wlan0 to network 503
,I/CLocInfoService(  834): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  834): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  834): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  834): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  834): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  834): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  834): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  834): Now, connected state.
E/WifiStateMachine(  834): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/WifiTrafficPoller(  834): evaluateTrafficStatsPolling
,I/CLocInfoService(  834): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  834): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  834): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  834): mBoosterFLAG : 0
I/WifiTrafficPoller(  834): current booster mode : FullMode
,E/WifiStateMachine(  834): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiNative-HAL(  834): callSECApiVoid - ID [212]
,E/WifiStateMachine(  834): ConnectedState Enter  mScreenOn=true scanperiod=20000
D/ConnectivityService(  834): Adding Route [fe80::/64 -> :: wlan0] to network 503
,I/CLocInfoService(  834): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  834): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  834): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,I/WifiStateMachine(  834): REQUEST_POWER_SAVE_ON
,E/ConnectivityService(  834): Unexpected mtu value: 0, wlan0
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/ConnectivityService(  834): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  834): updateSourceRoutes : add src route for:192.168.1.135
D/ResourcesManager( 7829): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,V/        (  277): QcRouteController
,W/ResourcesManager( 7829): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/        (  277): QcRouteController
,I/KnoxUsageLogPro( 7829): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7829): premStatus:2
,V/        (  277): QcRouteController
,I/KnoxUsageLogPro( 7829): isEulaShown : false
I/KnoxUsageLogPro( 7829): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,V/        (  277): QcRouteController
,E/Zygote  ( 7859): MountEmulatedStorage()
E/Zygote  ( 7859): v2
I/libpersona( 7859): KNOX_SDCARD checking this for 10088
I/libpersona( 7859): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7859 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  834): Killing 6915:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,V/        (  277): QcRouteController
,V/        (  277): QcRouteController
,V/        (  277): QcRouteController
,I/SELinux ( 7859): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7859): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7859): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,V/        (  277): QcRouteController
,W/libprocessgroup(  834): failed to open /acct/uid_10058/pid_6915/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7859): TimaSignature is unavailable
,D/ActivityThread( 7859): Added TimaKeyStore provider
,D/ConnectivityService(  834): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  834): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  834): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  834): updateNetworkInfo()
D/ConnectivityService(  834): calling update connectivity
E/ConnectivityService(  834): updateNetworkInfo()
D/ConnectivityService(  834): ignoring duplicate network state non-change
D/ConnectivityService(  834): ignoring duplicate network state non-change
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  834): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  834): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  834): Connected
D/ConnectivityService(  834): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  834): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  834): calling update connectivity
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  834): Validated
D/ConnectivityService(  834): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  834):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  834):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  834):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  834): currentScore = 0, newScore = 60
D/ConnectivityService(  834):    accepting network in place of null
D/ConnectivityService(  834): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  834): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  834): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  834): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  834): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/TelephonyNetworkFactory( 1474): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  834): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/EntConnectivity(  834): Not allowed due to - mEnabled false
D/ConnectivityService(  834): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  834): calling update connectivity
E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/SmartBondingService(  834): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  834): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  834): getSBEnabled() enabled =false
V/NetworkStats(  834): updateIfacesLocked()
D/NtpTrustedTime(  834): currentTimeMillis() cache hit
V/NetworkStats(  834): performPollLocked(flags=0x1)
D/SmartBondingService(  834): getSBEnabled() enabled =false
D/SmartBondingService(  834): getSBEnabled() enabled =false
D/ConnectivityService(  834): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkStatsFactory(  834): UpdateStatsForKnox
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  834): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
V/NetworkStats(  834): performPollLocked() took 3ms
D/NtpTrustedTime(  834): currentTimeMillis() cache hit
D/ConnectivityService(  834): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  834): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  834):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  834):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  834): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  834): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/ConnectivityService(  834): calling update connectivity
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
D/NtpTrustedTime(  834): currentTimeMillis() cache hit
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  834): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NtpTrustedTime(  834): currentTimeMillis() cache hit
D/NtpTrustedTime(  834): currentTimeMillis() cache hit
V/NetworkStats(  834): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  834): currentTimeMillis() cache hit
D/ConnectivityService(  834): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/NtpTrustedTime(  834): currentTimeMillis() cache hit
D/NtpTrustedTime(  834): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ResourcesManager( 7859): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/ActivityManager(  834): Killing 6251:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,D/Headlines( 5523): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5523): getCountryCode(): countryCode = DE
,D/Headlines( 5523): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5523): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5523): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5523): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5523): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,D/HeadlinesCardManager( 5523): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5523): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7883): MountEmulatedStorage()
E/Zygote  ( 7883): v2
I/libpersona( 7883): KNOX_SDCARD checking this for 10128
I/libpersona( 7883): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7883 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7883): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7883): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7883): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,W/libprocessgroup(  834): failed to open /acct/uid_1000/pid_6251/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7883): TimaSignature is unavailable
,D/ActivityThread( 7883): Added TimaKeyStore provider
,D/ResourcesManager( 7883): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7883): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7883): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7883): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  247): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7883): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WebViewFactory( 7883): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7883): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7883): Loading: webviewchromium
,I/LibraryLoader( 7883): Time to load native libraries: 4 ms (timestamps 2543-2547)
,I/LibraryLoader( 7883): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7883): Binding Chromium to main looper Looper (main, tid 1) {22d78bbd}
,I/LibraryLoader( 7883): Expected native library version number "",actual native library version number ""
,I/chromium( 7883): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7883): Initializing chromium process, renderers=0
,W/art     ( 7883): Attempt to remove local handle scope entry from IRT, ignoring
,D/ConnectivityService(  834): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  834): MasterInitialState.processMessage what=3
,D/SmartBondingService(  834): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  834): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  834): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  834): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  834): getSBEnabled() enabled =false
,D/SmartBondingService(  834): getSBEnabled() enabled =false
D/SmartBondingService(  834): getSBEnabled() enabled =false
I/CLocInfoService(  834): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  834): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  834): CLocinfo wifi true 
D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2264): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/chromium( 7883): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7883): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/chromium( 7883): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 2161): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2161): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7620): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3713): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3713): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/AudioManagerAndroid( 7883): Requires BLUETOOTH permission
,I/Adreno-EGL( 7883): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7883): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7883): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7883): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7883): Remote Branch: 
I/Adreno-EGL( 7883): Local Patches: 
I/Adreno-EGL( 7883): Reconstruct Branch: 
,I/art     (  834): Explicit concurrent mark sweep GC freed 63303(3MB) AllocSpace objects, 7(177KB) LOS objects, 30% free, 36MB/52MB, paused 1.186ms total 86.724ms
,D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  834): mCursor = null
,I/NSApplication( 7883): Starting up...
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/Zygote  ( 7947): MountEmulatedStorage()
E/Zygote  ( 7947): v2
I/libpersona( 7947): KNOX_SDCARD checking this for 10138
I/libpersona( 7947): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7947 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  834): Killing 6934:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,I/SELinux ( 7947): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7947): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7947): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  834): failed to open /acct/uid_10098/pid_6934/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7947): TimaSignature is unavailable
,D/ActivityThread( 7947): Added TimaKeyStore provider
,D/ResourcesManager( 7947): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7947): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7947): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7947): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7947): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7947): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7947): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7965): MountEmulatedStorage()
,E/Zygote  ( 7965): v2
I/libpersona( 7965): KNOX_SDCARD checking this for 10163
I/libpersona( 7965): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7965 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  834): Killing 6983:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,I/SELinux ( 7965): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7965): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7965): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,W/libprocessgroup(  834): failed to open /acct/uid_10033/pid_6983/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7965): TimaSignature is unavailable
,D/ActivityThread( 7965): Added TimaKeyStore provider
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 7965): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7965): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7965): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7965): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7965): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  834): exchangeData() failure , invalid userId
,D/RCPManagerService(  834): exchangeData() failure , invalid userId
,D/RCPManagerService(  834): exchangeData() failure , invalid userId
,D/ConnectivityService(  834): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  834): exchangeData() failure , invalid userId
,E/Zygote  ( 7990): MountEmulatedStorage()
I/libpersona( 7990): KNOX_SDCARD checking this for 10078
E/Zygote  ( 7990): v2
I/libpersona( 7990): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7990 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/SELinux ( 7990): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7990): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7990): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/TimaKeyStoreProvider( 7990): TimaSignature is unavailable
,D/ActivityThread( 7990): Added TimaKeyStore provider
D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  834): exchangeData() failure , invalid userId
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,D/RCPManagerService(  834): exchangeData() failure , invalid userId
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/ResourcesManager( 7990): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,I/ActivityManager(  834): Killing 6959:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,D/BadgeProvider( 7990): onCreate
,D/BadgeProvider( 7990): DatabaseHelper
,D/BadgeProvider( 7990): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,D/BadgeProvider( 7990): sendNotify entered. [uri] : content://com.sec.badge/apps/1
V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,D/BadgeProvider( 7990): sendNotify, [notify] : null
D/BadgeProvider( 7990): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7990): update, [BadgeCount] : badgecount=0
D/Launcher.Model( 1489): reloadBadges entered.
D/BadgeProvider( 7990): update, [UpdateCount] : 1
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7549): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7549): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7549): StateMachine : Current State = 1
V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,D/SecurityLogAgent( 7549): StateMachine : Changed Current State = 1
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,W/libprocessgroup(  834): failed to open /acct/uid_10099/pid_6959/cgroup.procs: No such file or directory
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,I/ActivityManager(  834): Killing 7020:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
D/com.peel.receiver.ConnectivityActionReceiver( 3641): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 3641): 
D/com.peel.receiver.ConnectivityActionReceiver( 3641): 
D/com.peel.receiver.ConnectivityActionReceiver( 3641): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 3641): 
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 3641): 
D/com.peel.receiver.ConnectivityActionReceiver( 3641): 
D/com.peel.receiver.ConnectivityActionReceiver( 3641):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 3641): 
D/com.peel.receiver.ConnectivityActionReceiver( 3641): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 3641): 
D/com.peel.receiver.ConnectivityActionReceiver( 3641): 
D/com.peel.receiver.ConnectivityActionReceiver( 3641): last run: 1450201652402 -- System.currentTimeMillis()-last_run: 31382813
D/com.peel.receiver.ConnectivityActionReceiver( 3641): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 3641): ... skip last_72_check
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,E/Zygote  ( 8019): MountEmulatedStorage()
E/Zygote  ( 8019): v2
I/libpersona( 8019): KNOX_SDCARD checking this for 10178
I/libpersona( 8019): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8019 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,I/SELinux ( 8019): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,I/SELinux ( 8019): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8019): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/TimaKeyStoreProvider( 8019): TimaSignature is unavailable
,D/ActivityThread( 8019): Added TimaKeyStore provider
,W/libprocessgroup(  834): failed to open /acct/uid_10003/pid_7020/cgroup.procs: No such file or directory
,V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
V/BitmapFactory( 7965): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/ResourcesManager( 8019): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  834): Killing 7039:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2460): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,D/ChimeraCfgMgr( 2460): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7189): notifyNetworkActivated
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 7189): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  834): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/libprocessgroup(  834): failed to open /acct/uid_10020/pid_7039/cgroup.procs: No such file or directory
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2460): [AccountUtils] Account not ready
W/Kids    ( 2460): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2460): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2460): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2460): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2460): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2460): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2460): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2460): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2460): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2460): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/ActivityManager(  834): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/hcjo    ( 7189): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7189): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7189): exit::IDLE
D/InitializeManagerStateMachine( 7189): entry::NETWORK_CHECK
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7189): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7189): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7189): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7189): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7189): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7189): entry::SUCCESS
D/hcjo    ( 7189): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1301): Starting #8
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/hcjo    ( 7189): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/hcjo    ( 7189): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7189): exit::SUCCESS
,D/InitializeManagerStateMachine( 7189): entry::IDLE
,I/Hs20UtilService( 1301): Starting #9
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,I/Hs20UtilService( 1301): Starting #10
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1301): Starting #11
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  834): callSECApi what=220
D/WifiStateMachine(  834): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 6777): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6777): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6777): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6777): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  248): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/DIAGMON_AGENT( 7677): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7677): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService(  834): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=834
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  834): [s] DisplayPowerCallbacks : onStateChanged()
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/lights  (  834): lcd : 8 +
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/lights  (  834): lcd : 8 -
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
E/Watchdog(  834): !@Sync 3
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/FOTA_Client( 7698): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7698): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/FOTA_Client( 7698): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7698): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7698): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/SMD     (  285): DCD ON
,I/KLMS-2.4.503: ( 7716): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7716): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450233035633
,I/KLMS-2.4.503: ( 7716): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7716): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7716): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7716): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/KLMS-2.4.503: ( 7716): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SO_AGENT( 7731): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7770): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SA      ( 7795): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7795): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7795): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7795): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7795): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7795): [SCU] == networkStateCheck == true
,I/SA      ( 7795): [DM] getCountryCodeFromCSC : DE
I/SA      ( 7795): isChinaCountryCode : false
I/SA      ( 7795): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7795): [OR] == networkStateCheck true ==
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7795): [OR] GetMyCountryZoneTask
,I/SA      ( 7795): [OR] onReceive END
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/SA      ( 7795): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 7317): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7317): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/KnoxUsageLogPro( 7829): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7829): premStatus:2
,I/SA      ( 7795): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/KnoxUsageLogPro( 7829): isEulaShown : false
I/KnoxUsageLogPro( 7829): KnoxUsageReceiver onReceive : not Processible, just return
,I/SA      ( 7795): [SSP] query invoked
,I/SA      ( 7795): [TPMU] GetMccFromDB : null
I/SA      ( 7795): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 7795): [TPM] isNoProxy(default) : true
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/Headlines( 5523): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5523): getCountryCode(): countryCode = DE
,D/Headlines( 5523): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5523): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5523): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5523): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5523): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5523): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5523): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/File    ( 7795): fail readDirectory() errno=2
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/QuickConnect( 7947): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7947): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7947): PeriphStartReceiver.onReceive - no need to start
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore out!
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/WifiStateMachine(  834): CMD_RSSI_POLL : out!
D/RCPManagerService(  834): exchangeData() failure , invalid userId
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/RCPManagerService(  834): exchangeData() failure , invalid userId
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7549): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7549): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7549): StateMachine : Current State = 1
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/SecurityLogAgent( 7549): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 3641): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 3641): 
D/com.peel.receiver.ConnectivityActionReceiver( 3641): 
D/com.peel.receiver.ConnectivityActionReceiver( 3641): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 3641): 
D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 3641): 
D/com.peel.receiver.ConnectivityActionReceiver( 3641): 
D/com.peel.receiver.ConnectivityActionReceiver( 3641):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 3641): 
D/com.peel.receiver.ConnectivityActionReceiver( 3641): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 3641): 
D/com.peel.receiver.ConnectivityActionReceiver( 3641): 
D/com.peel.receiver.ConnectivityActionReceiver( 3641): last run: 1450201652402 -- System.currentTimeMillis()-last_run: 31383395
D/com.peel.receiver.ConnectivityActionReceiver( 3641): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 3641): ... skip last_72_check
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ChimeraCfgMgr( 2460): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7189): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7189): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7189): exit::IDLE
D/InitializeManagerStateMachine( 7189): entry::NETWORK_CHECK
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7189): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7189): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7189): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7189): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7189): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7189): entry::SUCCESS
D/hcjo    ( 7189): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7189): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7189): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7189): exit::SUCCESS
D/InitializeManagerStateMachine( 7189): entry::IDLE
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,W/Kids    ( 2460): [AccountUtils] Account not ready
W/Kids    ( 2460): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2460): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2460): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2460): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2460): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2460): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2460): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2460): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2460): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2460): 	at java.lang.Thread.run(Thread.java:818)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
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
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
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
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/SA      ( 7795): [RC New] Execute method=[GET] start
,I/SA      ( 7795): [RC New] Security=[true]
,I/System.out( 7795): Thread-1290(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7795): Thread-1290(ApacheHTTPLog):isShipBuild true
,I/System.out( 7795): Thread-1290(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7489): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7489): 
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/WifiStateMachine(  834): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  834): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  834): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  834): identical MTU - not setting
D/ConnectivityService(  834): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  834): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,E/WifiStateMachine(  834): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
V/        (  277): QcRouteController
,D/SmartBondingService(  834): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  834): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  834): getSBEnabled() enabled =false
D/SmartBondingService(  834): getSBEnabled() enabled =false
D/SmartBondingService(  834): getSBEnabled() enabled =false
,V/        (  277): QcRouteController
,W/NetworkManagementService(  834): route cmd failed: 
W/NetworkManagementService(  834): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  834): '
W/NetworkManagementService(  834): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  834): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  834): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  834): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  834): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  834): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  834): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  834): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  834): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  834): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  834): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  834): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  834): calling update connectivity
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  834): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524295
,D/ConnectivityService(  834): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  834): calling update connectivity
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  834): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524295
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/SA      ( 7795): [RC New] [v2liruge] api execute + 667
,I/SA      ( 7795): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7795): AsyncTask #1 calls detatch()
,I/SA      ( 7795): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7795): [OCP] update openData : PL
,I/SA      ( 7795): [TPMU] getNetworkMcc : 
,I/SA      ( 7795): [SCU] saveMccToPreferece Start
I/SA      ( 7795): [SCU] RegionMCC : 260
I/SA      ( 7795): [SSP] query invoked
,I/SA      ( 7795): [TPMU] GetMccFromDB : null
I/SA      ( 7795): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7795): [SCU] saveMccToPreferece End
,I/SA      ( 7795): [RC New] executeRequest [v2liruge] end. 736
I/SA      ( 7795): [RC New] Execute end
,I/SA      ( 7795): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7795): [OR] GetMyCountryZoneTask Success
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  834): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  834): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7693): wlan0: sending IPv6 Router Solicitation
,V/AlarmManager(  834): waitForAlarm result :8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1718): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/Search.LoginHelper( 1585): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/WearableService( 4970): callingUid 10012, callindPid: 4970
,D/ResourcesManager( 7620): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7620): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7620): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7620): Using the GMSCore's GoogleHttpClient
,I/art     ( 1718): Explicit concurrent mark sweep GC freed 25816(1520KB) AllocSpace objects, 18(1458KB) LOS objects, 40% free, 17MB/29MB, paused 410us total 41.205ms
,D/WearableClient( 7620): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7620): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7620): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7620): WearableClientImpl.onPostInitHandler: done
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/GmsUtils( 7620): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7620): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 7620): Conditions not met for autocaching.
,I/MusicLeanback( 7620): Stop autocaching.
,E/ActivityThread( 7620): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2b2c1f35 that was originally bound here
E/ActivityThread( 7620): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2b2c1f35 that was originally bound here
E/ActivityThread( 7620): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7620): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7620): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7620): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7620): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7620): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7620): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7620): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7620): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7620): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7620): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7620): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7620): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7620): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7620): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7620): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7620): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7620): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7620): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7620): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7620): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7620): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7620): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7620): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7620): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : out!
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PowerManagerService(  834): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 834) eventTime = 107082
,D/PowerManagerService(  834): [s] UserActivityState : 2 -> 1
,D/PowerManagerService(  834): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=834 (0x0)
,D/PowerManagerService(  834): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=834, ws=WorkSource{10059}) (elapsedTime=3513)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
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
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
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
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/GAV4    ( 7883): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
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
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,I/SurfaceFlinger(  248): id=16 Removed Toast (8/8)
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,V/AlarmManager(  834): waitForAlarm result :4
,I/SurfaceFlinger(  248): id=16 Removed Toast (-2/8)
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/GCM     ( 1718): Connected
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1718): Message class com.google.f.a.a.p
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  834): SIOP:: AP = 400, PST = 427, CUR = 300
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6777): mConnectivityHandler : connected
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6777): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6777): ================================================
I/CSTORAGE( 6777):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6777): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6777): [GetString-S]
E/art     ( 6777): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6777): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6777): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6777): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6777): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6777): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6777): [ensureRegistration] - No Samsung account
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7693): wlan0: sending IPv6 Router Solicitation
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : out!
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : out!
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7693): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7693): wlan0: no IPv6 Routers available
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 7189): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7189): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7189): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7189): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7189): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7189): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7189): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7189): entry::IDLE
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7189): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 7189): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7189): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7189): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7189): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7189): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7189): entry::IDLE
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/FactoryTest( 6457): Not factory mode
D/FactoryTest( 6457): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6457): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6457): still no open session command from host, so toast
,W/ContextImpl( 6457): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 6457): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6457): Timeline: Activity_launch_request id:com.android.settings time:114284
,E/PersonaManagerService(  834): inState():  stateMachine is null !!
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  834): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  834): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 834  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  834): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SQLiteSecureOpenHelper( 3524): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3524): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/MTPRx   ( 6457): started activity for popup
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6457): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6457): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6457): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6457): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6457): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6457): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6457): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6457): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6457): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/InputMethodManagerService(  834): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/ActivityManager(  834): Invalid thumbnail dimensions: 576x576
,W/InputMethodManagerService(  834): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1486a26d attribute=null, token = android.os.BinderProxy@108229e0
,I/SQLiteSecureOpenHelper( 3524): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3524): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6457): dev.kiessupport is : TRUE
,D/Activity( 6457): performCreate Call secproduct feature valuefalse
,D/Activity( 6457): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ActivityManager(  834): post active user change for 0
D/KnoxTimeoutHandler(  834): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  834): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/Timeline( 7489): Timeline: Activity_idle id: android.os.BinderProxy@1adedad8 time:114535
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  834): CMD_RSSI_POLL : out!
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  834): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 834  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  834): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  834): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 834  pkgName : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  834): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 834  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  834): SIOP:: AP = 370, PST = 417, CUR = 300
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,I/ActivityManager(  834): Waited long enough for: ServiceRecord{222e1348 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  834): CMD_RSSI_POLL : out!
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,V/AlarmManager(  834): waitForAlarm result :4
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6669): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6669): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6669): [1] 5.onFinished: Scheduling replication attempt 3.
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : out!
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,V/AlarmManager(  834): waitForAlarm result :4
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : out!
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : out!
,V/AlarmManager(  834): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  834): SIOP:: AP = 340, PST = 403, CUR = 300
,D/X       (  834): broadcastSiopLevelIntent:: currentSiopLevel = -1
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,D/ContentApp( 1221):  LEVEL : -1,
,E/Zygote  ( 8178): MountEmulatedStorage()
E/Zygote  ( 8178): v2
I/libpersona( 8178): KNOX_SDCARD checking this for 10054
I/libpersona( 8178): KNOX_SDCARD not a persona
,I/ActivityManager(  834): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8178 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 8178): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8178): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8178): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  315): Explicit concurrent mark sweep GC freed 8751(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 833us total 34.137ms,
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 505us total 14.760ms
,D/TimaKeyStoreProvider( 8178): TimaSignature is unavailable
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 383us total 13.745ms
,D/ActivityThread( 8178): Added TimaKeyStore provider
,D/ResourcesManager( 8178): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,W/ResourcesManager( 8178): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8178): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8178): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8178): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8178): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 8178): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8178): core_num = 4
,W/linker  ( 8178): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8178): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8178): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,D/videowall-Global( 8178): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8178):  SIOP_LEVEL: -1
,I/ActivityManager(  834): Killing 7055:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,W/libprocessgroup(  834): failed to open /acct/uid_1000/pid_7055/cgroup.procs: No such file or directory
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  834): CMD_RSSI_POLL : out!
,D/PowerManagerService(  834): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  834): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  834): lcd : 5 +
,D/lights  (  834): lcd : 5 -
,D/lights  (  834): lcd : 1 +
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,D/lights  (  834): lcd : 1 -
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/Watchdog(  834): !@Sync 4
,E/SMD     (  285): DCD ON
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : out!
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,I/art     (  834): Explicit concurrent mark sweep GC freed 52462(3MB) AllocSpace objects, 17(2MB) LOS objects, 30% free, 36MB/52MB, paused 2.024ms total 181.783ms
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/SMD     (  285): DCD ON
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/DisplayPowerController(  834): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  834): CMD_RSSI_POLL : out!
,D/PowerManagerService(  834): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  834): Nap time (uid 1000)...
I/PowerManagerService(  834): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  834): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService(  834): [PWL] sb acquire: PowerManagerService.Broadcasts
D/InputManager-JNI(  834): setDeviceInteractive: 0
,D/PowerManagerService(  834): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI(  834): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/PowerManagerService(  834): handleSandman : startDream()
E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,E/PowerManagerService(  834): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService(  834): Sleeping (uid 1000)...
D/PowerManagerService(  834): [s] UserActivityState : 4 -> 0
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/PowerManagerService(  834): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService(  834): [input device light] handleInputDeviceLightOff
,D/InputManager-JNI(  834): sysfs_write +: /sys/class/input/event2/device/enabled: 0
I/SurfaceFlinger(  248): id=17 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  834): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  834): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  834): 	.unregisterCallback : 1, client=
D/SContextService(  834): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@242be843, Service = Auto Rotation, used = 1
,W/CAE     (  834): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  834): stop(ContextProvider.java:149)
V/CAE     (  834): clear(AutoRotationRunner.java:182)
,V/CAE     (  834): disable(AutoRotationRunner.java:171)
,I/CAE     (  834): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  834): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  297): sendContextData: -78, 7, 0, 0
,D/CAE     (  834): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  834): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  834): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  834): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  834): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  834): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  834): removeSContextService() : service = Auto Rotation
D/SContextService(  834): ===== SContext Service List =====
D/SContextManager(  834):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@11e8f57e, service=Auto Rotation
,D/KeyguardViewMediator( 1169): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1169): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1169): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1169): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/KeyguardViewMediator( 1169): timeout : 5000
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/KeyguardViewMediator( 1169): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1169): handleNotifyScreenOff
,D/DisplayPowerController(  834): ColorFade: onAnimationStart
,D/DisplayPowerController(  834): getFinalBrightness : 8 -> 0
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
,D/lights  (  834): lcd : 0 +
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 0
,D/LightsService(  834): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 834) 
D/LightsService(  834): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  834): [SvcLED]  onSensorChanged::light value = 0
,I/SQLiteSecureOpenHelper( 3524): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3524): getDatabaseLocked(b,b,pwd)...
,D/SensorManager(  834): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  834): unregisterListener ::   
D/BatteryService(  834): turn on LED for fully charged
,I/CAE     (  834): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  834): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  834): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  834): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  297): sendContextData: -76, 13, -46, 0
,I/CAE     (  834): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 2, 31, 9,
D/SensorHubManager(  834): SendSensorHubData: send data = -63, 14, 2, 31, 9
D/Sensorhubs(  297): sendContextData: -63, 14, 2, 31, 9
,D/lights  (  834): lcd : 0 -
,D/lights  (  834): led_pattern : 5 +
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_SCREEN_OFF
,D/lights  (  834): led_pattern : 5 -
,D/LightsService(  834): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/MotionRecognitionService(  834):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  834): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  834): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  834): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,D/NotificationService(  834): ACTION_SCREEN_OFF
E/WifiStateMachine(  834): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  834): do suspend true
D/LightsService(  834): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 834) 
,D/LightsService(  834): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  834): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  834): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  834): unregisterListener ::   
,D/LightsService(  834): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  291): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  834): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  834): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  834): Bridge Server is not available
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1169): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1169): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  834): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler(  834): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1468): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1169):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1169): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1169): dismissHelpPopup 
,D/accuweather( 2264): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2264): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2264): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,W/ActivityManager(  834): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  834): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  834): [PWL] sb release: PowerManagerService.Broadcasts
,E/LightSensor(  834): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  834): mCallbacks.updateBrightness()
D/DisplayPowerController(  834): getFinalBrightness : 8 -> 0
,D/SSRM:m  (  834): SIOP:: AP = 330, PST = 387, CUR = 300
,D/DisplayPowerState(  834): !@ ColorFade entry
D/DisplayPowerController(  834): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  834): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  834): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
E/LightSensor(  834): Light old sensor_state 8705, new sensor_state : 8193 en : 0
D/AutomaticBrightnessController(  834): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/AutomaticBrightnessController(  834): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  834): unregisterListener ::   
E/Sensors (  834): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  834): unregisterListener ::   
,D/DisplayPowerController(  834): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  834): getFinalBrightness : 0 -> 0
D/SurfaceFlinger(  248): Set power mode=0, type=0 flinger=0xb6a62000
I/DisplayManagerService(  834): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/qdhwcomposer(  248): hwc_blank: Blanking display: 0
V/ActivityManager(  834): Display changed displayId=0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/StatusBar.NetworkController( 1169): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
,I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1228406016)
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1228406016) wakelock released: 1, error no: 22
I/rmt_storage(  273): 
,I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
,I/qdhwcomposer(  248): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  248): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  834): Excessive delay in setPowerMode(): 265ms
D/PowerManagerService(  834): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/MISC PowerHAL(  834): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  834): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  834): Got set_interactive hint
,I/PowerManagerService(  834): [PWL] Off : 0s ago
,I/PowerManagerService(  834): [PWL]   PowerManagerService.Display: ref count=2
,I/PowerManagerService(  834): [PWL]     mDisplayReady : false
,D/DisplayPowerController(  834): getFinalBrightness : 0 -> 0
,D/PowerManagerService(  834): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  834): [PWL] sb release: PowerManagerService.Display
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager(  834): waitForAlarm result :4
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ProcessCpuTracker(  834): Skipping unknown process pid 8240
,W/ProcessCpuTracker(  834): Skipping unknown process pid 8241
W/ProcessCpuTracker(  834): Skipping unknown process pid 8243
W/ProcessCpuTracker(  834): Skipping unknown process pid 8244
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6669): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6669): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6669): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager(  834): waitForAlarm result :4
,D/KeyguardViewMediator( 1169): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/KeyguardViewMediator( 1169): doKeyguard: not showing because lockscreen is off
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 5s ago
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 330, PST = 375, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  834): waitForAlarm result :4
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  834): stay LED for fully charged
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  834): [PWL] Off : 15s ago
,I/PowerManagerService(  834): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  834): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  834): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.plus.content.EsProvider/com.google/eM_ADDR' (uid=1000, pid=834, ws=WorkSource{10135}) (elapsedTime=158)
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1718): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6642): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at dsf.a(PG:807)
E/HttpOperation( 6642): 	at fhk.a(PG:1126)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 8 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 10 more
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6642): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at ieo.a(PG:43)
E/HttpOperation( 6642): 	at iep.a(PG:93)
E/HttpOperation( 6642): 	at fhn.a(PG:59)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
,E/ExperimentLoader( 6642): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): 	at kfv.a(PG:65)
E/ExperimentLoader( 6642): 	at kff.u(PG:385)
E/ExperimentLoader( 6642): 	at kfb.a(PG:29)
E/ExperimentLoader( 6642): 	at kff.l(PG:132)
E/ExperimentLoader( 6642): 	at ieo.a(PG:43)
E/ExperimentLoader( 6642): 	at iep.a(PG:93)
E/ExperimentLoader( 6642): 	at fhn.a(PG:59)
E/ExperimentLoader( 6642): 	at lex.a(PG:85)
E/ExperimentLoader( 6642): 	at lex.b(PG:132)
E/ExperimentLoader( 6642): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6642): 	at fhk.a(PG:908)
E/ExperimentLoader( 6642): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6642): 	at ihi.a(PG:22)
E/ExperimentLoader( 6642): 	at kft.a(PG:91)
E/ExperimentLoader( 6642): 	at kfv.a(PG:62)
E/ExperimentLoader( 6642): 	... 12 more
E/ExperimentLoader( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6642): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6642): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6642): 	at ihi.a(PG:19)
E/ExperimentLoader( 6642): 	... 14 more
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6642): [getaccountstatus] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at ixd.a(PG:248)
E/HttpOperation( 6642): 	at ixd.b(PG:206)
E/HttpOperation( 6642): 	at ixd.a(PG:175)
E/HttpOperation( 6642): 	at fig.a(PG:78)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
,E/EsSyncAdapterService( 6642): Sync failure
E/EsSyncAdapterService( 6642): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6642): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6642): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6642): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6642): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6642): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6642): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6642): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6642): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6642): 	... 10 more
E/EsSyncAdapterService( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6642): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6642): 	... 12 more
E/EsSyncAdapterService( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6642): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6642): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6642): 	... 14 more
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  834): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 124992, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  834): mCursor = null
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 320, PST = 366, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager(  834): waitForAlarm result :4
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6669): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6669): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6669): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Watchdog(  834): !@Sync 5
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 320, PST = 357, CUR = 300
,I/PowerManagerService(  834): [PWL] Off : 30s ago
,E/SMD     (  285): DCD ON
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 310, PST = 348, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :4
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  834): stay LED for fully charged
D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1718): Vacuum at: now=1450233114377 tag=VacuumService
,I/GoogleURLConnFactory( 1718): Using platform SSLCertificateSocketFactory
,W/Uploader( 1718): No account for auth token provided
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1718): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1718): (HTTPLog)-Static: isShipBuild true
I/System.out( 1718): (HTTPLog)-Thread-210-420867038: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1718): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1718, getuid(): 10012
,I/qtaguid ( 1718): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1718, getuid(): 10012
,V/AlarmManager(  834): waitForAlarm result :4
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7416): Starting books sync, d
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1718): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1718): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1718): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1718): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1718): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1718): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1718): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1718): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1718): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1718): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/qtaguid ( 1718): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1718, getuid(): 10012
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6669): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6669): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6669): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1718): No account for auth token provided
,I/qtaguid ( 1718): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1718, getuid(): 10012
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1718): creating new AssetManager and set to /system/app/Books/Books.apk
,W/Uploader( 1718): No account for auth token provided
,I/qtaguid ( 1718): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1718, getuid(): 10012
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
E/HttpHelper( 7416): null auth token
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,W/Uploader( 1718): No account for auth token provided
,I/qtaguid ( 1718): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1718, getuid(): 10012
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,W/Uploader( 1718):  no longer exists, so no auth token.
,I/qtaguid ( 1718): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1718, getuid(): 10012
,I/qtaguid ( 7416): Untagging socket 34
,W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
,W/ApiaryClient( 7416): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=964636391042043872&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7416): null auth token
,D/PanelView( 1169): There is/are notification(s) 
I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,I/qtaguid ( 7416): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,I/qtaguid ( 7416): Untagging socket 34
,W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
W/ApiaryClient( 7416): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=964636391042043872&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
E/SMD     (  285): DCD ON
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7416): null auth token
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/qtaguid ( 7416): Untagging socket 34
,W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
,W/ApiaryClient( 7416): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=964636391042043872&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/BooksSync( 7416): Soft error
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=964636391042043872&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7416): Headers suppressed
E/BooksSync( 7416): 
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7416): Sync error
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=964636391042043872&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7416): Headers suppressed
E/BooksSync( 7416): 
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7416): Finished books sync
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  834): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 159843, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  834): Explicit concurrent mark sweep GC freed 55187(2MB) AllocSpace objects, 24(839KB) LOS objects, 30% free, 36MB/52MB, paused 1.533ms total 127.156ms
,D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  834): mCursor = null
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1718): Explicit concurrent mark sweep GC freed 46005(2MB) AllocSpace objects, 58(3MB) LOS objects, 40% free, 18MB/30MB, paused 706us total 37.994ms
,D/ResourcesManager( 1718): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
E/HttpOperation( 6642): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at dsf.a(PG:807)
E/HttpOperation( 6642): 	at fhk.a(PG:1126)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 8 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 10 more
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  285): DCD ON
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6642): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at ieo.a(PG:43)
E/HttpOperation( 6642): 	at iep.a(PG:93)
E/HttpOperation( 6642): 	at fhn.a(PG:59)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
D/SSRM:m  (  834): SIOP:: AP = 310, PST = 341, CUR = 300
E/ExperimentLoader( 6642): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): 	at kfv.a(PG:65)
E/ExperimentLoader( 6642): 	at kff.u(PG:385)
E/ExperimentLoader( 6642): 	at kfb.a(PG:29)
E/ExperimentLoader( 6642): 	at kff.l(PG:132)
E/ExperimentLoader( 6642): 	at ieo.a(PG:43)
E/ExperimentLoader( 6642): 	at iep.a(PG:93)
E/ExperimentLoader( 6642): 	at fhn.a(PG:59)
E/ExperimentLoader( 6642): 	at lex.a(PG:85)
E/ExperimentLoader( 6642): 	at lex.b(PG:132)
E/ExperimentLoader( 6642): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6642): 	at fhk.a(PG:908)
E/ExperimentLoader( 6642): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6642): 	at ihi.a(PG:22)
E/ExperimentLoader( 6642): 	at kft.a(PG:91)
E/ExperimentLoader( 6642): 	at kfv.a(PG:62)
E/ExperimentLoader( 6642): 	... 12 more
E/ExperimentLoader( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6642): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6642): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6642): 	at ihi.a(PG:19)
E/ExperimentLoader( 6642): 	... 14 more
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/PowerManagerService(  834): [PWL] Off : 50s ago
,I/PowerManagerService(  834): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  834): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  834): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.plus.content.EsProvider/com.google/eM_ADDR' (uid=1000, pid=834, ws=WorkSource{10135}) (elapsedTime=649)
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  834): waitForAlarm result :8
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6642): [getaccountstatus] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at ixd.a(PG:248)
E/HttpOperation( 6642): 	at ixd.b(PG:206)
E/HttpOperation( 6642): 	at ixd.a(PG:175)
E/HttpOperation( 6642): 	at fig.a(PG:78)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
,E/EsSyncAdapterService( 6642): Sync failure
E/EsSyncAdapterService( 6642): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6642): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6642): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6642): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6642): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6642): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6642): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6642): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6642): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6642): 	... 10 more
E/EsSyncAdapterService( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6642): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6642): 	... 12 more
E/EsSyncAdapterService( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6642): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6642): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6642): 	... 14 more
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  834): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 183324, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  834): mCursor = null
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  834): !@Sync 6
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 310, PST = 334, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 310, PST = 325, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  834): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,I/PowerManagerService(  834): [PWL] Off : 75s ago
,I/PowerManagerService(  834): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  834): [PWL]     mWakeLockSummary : 0x1
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  834): stay LED for fully charged
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 300, PST = 318, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  834): !@Sync 7
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:m  (  834): SIOP:: AP = 300, PST = 314, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  834): SIOP:: AP = 300, PST = 311, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 105s ago
,V/AlarmManager(  834): waitForAlarm result :4
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7416): Starting books sync, d
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1718): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7416): null auth token
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,I/qtaguid ( 7416): Untagging socket 34
,W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
,W/ApiaryClient( 7416): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8861088032431437435&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7416): null auth token
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,E/SMD     (  285): DCD ON
,I/qtaguid ( 7416): Untagging socket 34
,W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
,W/ApiaryClient( 7416): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8861088032431437435&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7416): null auth token
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,I/qtaguid ( 7416): Untagging socket 34
,W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
,W/ApiaryClient( 7416): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8861088032431437435&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7416): Soft error
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8861088032431437435&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7416): Headers suppressed
E/BooksSync( 7416): 
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7416): Sync error
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8861088032431437435&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7416): Headers suppressed
E/BooksSync( 7416): 
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7416): Finished books sync
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  834): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 217062, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  834): mCursor = null
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager(  834): waitForAlarm result :8
,D/SSRM:m  (  834): SIOP:: AP = 300, PST = 308, CUR = 300
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,E/Watchdog(  834): !@Sync 8
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 300, PST = 306, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  834): SIOP:: AP = 300, PST = 304, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager(  834): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6642): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at dsf.a(PG:807)
E/HttpOperation( 6642): 	at fhk.a(PG:1126)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 8 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 10 more
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6642): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at ieo.a(PG:43)
E/HttpOperation( 6642): 	at iep.a(PG:93)
E/HttpOperation( 6642): 	at fhn.a(PG:59)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
E/ExperimentLoader( 6642): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): 	at kfv.a(PG:65)
E/ExperimentLoader( 6642): 	at kff.u(PG:385)
E/ExperimentLoader( 6642): 	at kfb.a(PG:29)
E/ExperimentLoader( 6642): 	at kff.l(PG:132)
E/ExperimentLoader( 6642): 	at ieo.a(PG:43)
E/ExperimentLoader( 6642): 	at iep.a(PG:93)
E/ExperimentLoader( 6642): 	at fhn.a(PG:59)
E/ExperimentLoader( 6642): 	at lex.a(PG:85)
E/ExperimentLoader( 6642): 	at lex.b(PG:132)
E/ExperimentLoader( 6642): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6642): 	at fhk.a(PG:908)
E/ExperimentLoader( 6642): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6642): 	at ihi.a(PG:22)
E/ExperimentLoader( 6642): 	at kft.a(PG:91)
E/ExperimentLoader( 6642): 	at kfv.a(PG:62)
E/ExperimentLoader( 6642): 	... 12 more
E/ExperimentLoader( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6642): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6642): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6642): 	at ihi.a(PG:19)
E/ExperimentLoader( 6642): 	... 14 more
D/PanelView( 1169): There is/are notification(s) 
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6642): [getaccountstatus] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at ixd.a(PG:248)
E/HttpOperation( 6642): 	at ixd.b(PG:206)
E/HttpOperation( 6642): 	at ixd.a(PG:175)
E/HttpOperation( 6642): 	at fig.a(PG:78)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
,E/EsSyncAdapterService( 6642): Sync failure
E/EsSyncAdapterService( 6642): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6642): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6642): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6642): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6642): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6642): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6642): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6642): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6642): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6642): 	... 10 more
E/EsSyncAdapterService( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6642): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6642): 	... 12 more
E/EsSyncAdapterService( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6642): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6642): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6642): 	... 14 more
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  834): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 248263, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  834): mCursor = null
,E/SMD     (  285): DCD ON
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 140s ago
,D/SSRM:m  (  834): SIOP:: AP = 300, PST = 303, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 9
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 300, PST = 302, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  834): SIOP:: AP = 300, PST = 301, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :4
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): stay LED for fully charged
D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :8
,D/SSRM:m  (  834): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  285): DCD ON
,D/TimaService(  834): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  834): TimaServiceHandler.handleMessage what =1
,D/TimaService(  834): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  834): initializing...
,I/TLC_TIMA_PKM_initialize(  834): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  834): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  834): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  834): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  834): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  834): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  834): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  834): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  834): App is not loaded in QSEE
,D/QSEECOMAPI: (  834): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  834): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  834): Trustlet response is completed
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,E/Watchdog(  834): !@Sync 10
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  834): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  834): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  834): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  834): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 180s ago
,D/SSRM:m  (  834): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  285): DCD ON
,I/jxcore-log( 7489): Connected to the server!
I/jxcore-log( 7489): 
,I/chromium( 7489): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  285): DCD ON
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  834): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager(  834): waitForAlarm result :4
,E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  834): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8459 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 8459): MountEmulatedStorage()
E/Zygote  ( 8459): v2
I/libpersona( 8459): KNOX_SDCARD checking this for 10081
I/libpersona( 8459): KNOX_SDCARD not a persona
,I/SELinux ( 8459): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8459): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8459): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7416): Starting books sync, d
,D/TimaKeyStoreProvider( 8459): TimaSignature is unavailable
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ActivityThread( 8459): Added TimaKeyStore provider
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 8459): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7416): null auth token
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7416): Untagging socket 34
,W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
,W/ApiaryClient( 7416): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8150141634518259968&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7416): null auth token
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,I/qtaguid ( 7416): Untagging socket 34
,W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
,W/ApiaryClient( 7416): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8150141634518259968&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7416): null auth token
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,I/qtaguid ( 7416): Untagging socket 34
,W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
,W/ApiaryClient( 7416): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8150141634518259968&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7416): Soft error
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8150141634518259968&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7416): Headers suppressed
E/BooksSync( 7416): 
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/SMD     (  285): DCD ON
,E/BooksSync( 7416): Sync error
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8150141634518259968&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7416): Headers suppressed
E/BooksSync( 7416): 
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7416): Finished books sync
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  834): Killing 7074:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,D/SyncManager(  834): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 307207, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/libprocessgroup(  834): failed to open /acct/uid_10112/pid_7074/cgroup.procs: No such file or directory
,I/art     (  834): Explicit concurrent mark sweep GC freed 58015(3MB) AllocSpace objects, 62(1772KB) LOS objects, 30% free, 36MB/52MB, paused 1.767ms total 172.617ms
D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  834): mCursor = null
,D/SSRM:m  (  834): SIOP:: AP = 300, PST = 300, CUR = 300
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  834): !@Sync 11
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  834): SIOP:: AP = 300, PST = 300, CUR = 300
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1718): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6669): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6669): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6669): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6669): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6669): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6669): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6669): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 6669): Ignoring header User-Agent because its value was null.
,I/System.out( 6669): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6669): (HTTPLog)-Static: isShipBuild true
I/System.out( 6669): (HTTPLog)-Thread-1093-46757237: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/SSRM:m  (  834): SIOP:: AP = 300, PST = 300, CUR = 300,
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 225s ago
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager(  834): waitForAlarm result :4
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  834): waitForAlarm result :8
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 299, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  834): !@Sync 12
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 298, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 297, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  834): stay LED for fully charged
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6642): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at dsf.a(PG:807)
E/HttpOperation( 6642): 	at fhk.a(PG:1126)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 8 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 10 more
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/art     ( 1718): Explicit concurrent mark sweep GC freed 39467(2MB) AllocSpace objects, 31(2MB) LOS objects, 39% free, 18MB/30MB, paused 899us total 97.971ms
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1718): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
E/HttpOperation( 6642): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at ieo.a(PG:43)
E/HttpOperation( 6642): 	at iep.a(PG:93)
E/HttpOperation( 6642): 	at fhn.a(PG:59)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/ExperimentLoader( 6642): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): 	at kfv.a(PG:65)
E/ExperimentLoader( 6642): 	at kff.u(PG:385)
E/ExperimentLoader( 6642): 	at kfb.a(PG:29)
E/ExperimentLoader( 6642): 	at kff.l(PG:132)
E/ExperimentLoader( 6642): 	at ieo.a(PG:43)
E/ExperimentLoader( 6642): 	at iep.a(PG:93)
E/ExperimentLoader( 6642): 	at fhn.a(PG:59)
E/ExperimentLoader( 6642): 	at lex.a(PG:85)
E/ExperimentLoader( 6642): 	at lex.b(PG:132)
E/ExperimentLoader( 6642): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6642): 	at fhk.a(PG:908)
E/ExperimentLoader( 6642): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6642): 	at ihi.a(PG:22)
E/ExperimentLoader( 6642): 	at kft.a(PG:91)
E/ExperimentLoader( 6642): 	at kfv.a(PG:62)
E/ExperimentLoader( 6642): 	... 12 more
E/ExperimentLoader( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6642): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6642): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6642): 	at ihi.a(PG:19)
E/ExperimentLoader( 6642): 	... 14 more
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6642): [getaccountstatus] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at ixd.a(PG:248)
E/HttpOperation( 6642): 	at ixd.b(PG:206)
E/HttpOperation( 6642): 	at ixd.a(PG:175)
E/HttpOperation( 6642): 	at fig.a(PG:78)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
,E/EsSyncAdapterService( 6642): Sync failure
E/EsSyncAdapterService( 6642): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6642): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6642): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6642): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6642): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6642): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6642): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6642): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6642): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6642): 	... 10 more
E/EsSyncAdapterService( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6642): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6642): 	... 12 more
E/EsSyncAdapterService( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6642): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6642): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6642): 	... 14 more
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,D/SyncManager(  834): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 394772, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2854): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  834): mCursor = null
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 296, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 13
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 275s ago
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :4
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  834): stay LED for fully charged
D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :8
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 293, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  834): !@Sync 14
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager(  834): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  834): stay LED for fully charged
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7416): Starting books sync, d
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1718): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7416): null auth token
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7416): Untagging socket 34
,W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
,W/ApiaryClient( 7416): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7829174280926921118&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7416): null auth token
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/qtaguid ( 7416): Untagging socket 34
,W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
,W/ApiaryClient( 7416): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7829174280926921118&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7416): null auth token
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,I/qtaguid ( 7416): Untagging socket 34
,W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
,W/ApiaryClient( 7416): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7829174280926921118&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/BooksSync( 7416): Soft error
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7829174280926921118&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7416): Headers suppressed
E/BooksSync( 7416): 
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7416): Sync error
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7829174280926921118&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7416): Headers suppressed
E/BooksSync( 7416): 
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7416): Finished books sync
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  834): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 458074, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2854): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2854): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  834): mCursor = null
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  834): !@Sync 15
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 330s ago
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,D/BatteryService(  834): stay LED for fully charged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/bootchecker(  321): bootchecker wake up!!
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  834): waitForAlarm result :8
,V/AlarmManager(  834): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): stay LED for fully charged
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  834): !@Sync 16
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
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
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 17
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 390s ago
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :8
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  834): !@Sync 18
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/Atfwd_Daemon(  326): Stop the daemon....
,E/Watchdog(  834): !@Sync 19
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 455s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/TimaService(  834): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  834): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  834): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  834): !@Sync 20
,E/SMD     (  285): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  834): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  834): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  834): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  834): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ActivityManager(  834): Killing 7092:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,W/libprocessgroup(  834): failed to open /acct/uid_10118/pid_7092/cgroup.procs: No such file or directory
,V/AlarmManager(  834): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  834): stay LED for fully charged
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6642): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at dsf.a(PG:807)
E/HttpOperation( 6642): 	at fhk.a(PG:1126)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 8 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 10 more
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6642): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at ieo.a(PG:43)
E/HttpOperation( 6642): 	at iep.a(PG:93)
E/HttpOperation( 6642): 	at fhn.a(PG:59)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/ExperimentLoader( 6642): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): 	at kfv.a(PG:65)
E/ExperimentLoader( 6642): 	at kff.u(PG:385)
E/ExperimentLoader( 6642): 	at kfb.a(PG:29)
E/ExperimentLoader( 6642): 	at kff.l(PG:132)
E/ExperimentLoader( 6642): 	at ieo.a(PG:43)
E/ExperimentLoader( 6642): 	at iep.a(PG:93)
E/ExperimentLoader( 6642): 	at fhn.a(PG:59)
E/ExperimentLoader( 6642): 	at lex.a(PG:85)
E/ExperimentLoader( 6642): 	at lex.b(PG:132)
E/ExperimentLoader( 6642): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6642): 	at fhk.a(PG:908)
E/ExperimentLoader( 6642): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6642): 	at ihi.a(PG:22)
E/ExperimentLoader( 6642): 	at kft.a(PG:91)
E/ExperimentLoader( 6642): 	at kfv.a(PG:62)
E/ExperimentLoader( 6642): 	... 12 more
E/ExperimentLoader( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6642): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6642): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6642): 	at ihi.a(PG:19)
E/ExperimentLoader( 6642): 	... 14 more
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6642): [getaccountstatus] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at ixd.a(PG:248)
E/HttpOperation( 6642): 	at ixd.b(PG:206)
E/HttpOperation( 6642): 	at ixd.a(PG:175)
E/HttpOperation( 6642): 	at fig.a(PG:78)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
,E/EsSyncAdapterService( 6642): Sync failure
E/EsSyncAdapterService( 6642): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6642): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6642): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6642): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6642): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6642): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6642): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6642): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6642): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6642): 	... 10 more
E/EsSyncAdapterService( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6642): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6642): 	... 12 more
E/EsSyncAdapterService( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6642): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6642): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6642): 	... 14 more
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  834): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 636637, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  834): Explicit concurrent mark sweep GC freed 62589(4MB) AllocSpace objects, 106(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.689ms total 153.414ms
D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  834): mCursor = null
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 21
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 525s ago
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :4
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :8
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 22
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7416): Starting books sync, d
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7416): null auth token
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,E/Watchdog(  834): !@Sync 23
,I/qtaguid ( 7416): Untagging socket 34
,W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
,W/ApiaryClient( 7416): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6761341275547623911&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpHelper( 7416): null auth token
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,I/qtaguid ( 7416): Tagging socket 40 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,I/qtaguid ( 7416): Untagging socket 34
,W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
,W/ApiaryClient( 7416): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6761341275547623911&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7416): null auth token
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,I/qtaguid ( 7416): Untagging socket 34
,W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
,W/ApiaryClient( 7416): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6761341275547623911&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/BooksSync( 7416): Soft error
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6761341275547623911&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7416): Headers suppressed
E/BooksSync( 7416): 
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7416): Sync error
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6761341275547623911&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7416): Headers suppressed
E/BooksSync( 7416): 
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7416): Finished books sync
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  834): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 702878, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  834): mCursor = null
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :8
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  834): stay LED for fully charged
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog(  834): !@Sync 24
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 600s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  834): !@Sync 25
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :8
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 26
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 680s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 27
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 28
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 29
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 765s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/TimaService(  834): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  834): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  834): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 30
,E/SMD     (  285): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  834): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  834): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  834): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  834): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 31
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 32
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 855s ago
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 33
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :4
,D/LightsService(  834): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  834): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  834): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/GCM     ( 1718): Message class com.google.f.a.a.i
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  834): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  834): [SvcLED]  onSensorChanged::light value = 0
E/LightSensor(  834): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  834): unregisterListener ::   
D/LightsService(  834): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :8
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 34
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 35
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 950s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 36
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6642): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at dsf.a(PG:807)
E/HttpOperation( 6642): 	at fhk.a(PG:1126)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 8 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 10 more
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6642): [getaccountstatus] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at ixd.a(PG:248)
E/HttpOperation( 6642): 	at ixd.b(PG:206)
E/HttpOperation( 6642): 	at ixd.a(PG:175)
E/HttpOperation( 6642): 	at fig.a(PG:78)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
,E/EsSyncAdapterService( 6642): Sync failure
E/EsSyncAdapterService( 6642): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6642): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6642): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6642): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6642): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6642): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6642): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6642): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6642): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6642): 	... 10 more
E/EsSyncAdapterService( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6642): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6642): 	... 12 more
E/EsSyncAdapterService( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6642): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6642): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6642): 	... 14 more
D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  834): mCursor = null
,I/art     ( 1718): Explicit concurrent mark sweep GC freed 37181(2MB) AllocSpace objects, 28(2MB) LOS objects, 39% free, 18MB/30MB, paused 1.250ms total 54.330ms
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1718): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6642): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at dsf.a(PG:807)
E/HttpOperation( 6642): 	at fhk.a(PG:1126)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 8 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 10 more
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6642): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at ieo.a(PG:43)
E/HttpOperation( 6642): 	at iep.a(PG:93)
E/HttpOperation( 6642): 	at fhn.a(PG:59)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
,E/ExperimentLoader( 6642): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): 	at kfv.a(PG:65)
E/ExperimentLoader( 6642): 	at kff.u(PG:385)
E/ExperimentLoader( 6642): 	at kfb.a(PG:29)
E/ExperimentLoader( 6642): 	at kff.l(PG:132)
E/ExperimentLoader( 6642): 	at ieo.a(PG:43)
E/ExperimentLoader( 6642): 	at iep.a(PG:93)
E/ExperimentLoader( 6642): 	at fhn.a(PG:59)
E/ExperimentLoader( 6642): 	at lex.a(PG:85)
E/ExperimentLoader( 6642): 	at lex.b(PG:132)
E/ExperimentLoader( 6642): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6642): 	at fhk.a(PG:908)
E/ExperimentLoader( 6642): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6642): 	at ihi.a(PG:22)
E/ExperimentLoader( 6642): 	at kft.a(PG:91)
E/ExperimentLoader( 6642): 	at kfv.a(PG:62)
E/ExperimentLoader( 6642): 	... 12 more
E/ExperimentLoader( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6642): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6642): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6642): 	at ihi.a(PG:19)
E/ExperimentLoader( 6642): 	... 14 more
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6642): [getaccountstatus] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at ixd.a(PG:248)
E/HttpOperation( 6642): 	at ixd.b(PG:206)
E/HttpOperation( 6642): 	at ixd.a(PG:175)
E/HttpOperation( 6642): 	at fig.a(PG:78)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
,E/EsSyncAdapterService( 6642): Sync failure
E/EsSyncAdapterService( 6642): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6642): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6642): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6642): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6642): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6642): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6642): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6642): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6642): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6642): 	... 10 more
E/EsSyncAdapterService( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6642): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6642): 	... 12 more
E/EsSyncAdapterService( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6642): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6642): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6642): 	... 14 more
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  834): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 637908, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  834): mCursor = null
,E/SMD     (  285): DCD ON
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 37
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,D/BatteryService(  834): stay LED for fully charged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :8
,V/AlarmManager(  834): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 38
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :4
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  834): stay LED for fully charged
D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6642): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at dsf.a(PG:807)
E/HttpOperation( 6642): 	at fhk.a(PG:1126)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 8 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 10 more
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6642): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at ieo.a(PG:43)
E/HttpOperation( 6642): 	at iep.a(PG:93)
E/HttpOperation( 6642): 	at fhn.a(PG:59)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
,E/ExperimentLoader( 6642): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): 	at kfv.a(PG:65)
E/ExperimentLoader( 6642): 	at kff.u(PG:385)
E/ExperimentLoader( 6642): 	at kfb.a(PG:29)
E/ExperimentLoader( 6642): 	at kff.l(PG:132)
E/ExperimentLoader( 6642): 	at ieo.a(PG:43)
E/ExperimentLoader( 6642): 	at iep.a(PG:93)
E/ExperimentLoader( 6642): 	at fhn.a(PG:59)
E/ExperimentLoader( 6642): 	at lex.a(PG:85)
E/ExperimentLoader( 6642): 	at lex.b(PG:132)
E/ExperimentLoader( 6642): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6642): 	at fhk.a(PG:908)
E/ExperimentLoader( 6642): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6642): 	at ihi.a(PG:22)
E/ExperimentLoader( 6642): 	at kft.a(PG:91)
E/ExperimentLoader( 6642): 	at kfv.a(PG:62)
E/ExperimentLoader( 6642): 	... 12 more
E/ExperimentLoader( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6642): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6642): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6642): 	at ihi.a(PG:19)
E/ExperimentLoader( 6642): 	... 14 more
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6642): [getaccountstatus] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at ixd.a(PG:248)
E/HttpOperation( 6642): 	at ixd.b(PG:206)
E/HttpOperation( 6642): 	at ixd.a(PG:175)
E/HttpOperation( 6642): 	at fig.a(PG:78)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
E/EsSyncAdapterService( 6642): Sync failure,
E/EsSyncAdapterService( 6642): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6642): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6642): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6642): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6642): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:908),
E/EsSyncAdapterService( 6642): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6642): ,	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6642): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6642): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6642): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6642): 	... 10 more
E/EsSyncAdapterService( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6642): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6642): 	... 12 more
E/EsSyncAdapterService( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6642): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6642): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6642): 	... 14 more
,D/PanelView( 1169): There is/are notification(s) 
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  834): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 1152196, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  834): Explicit concurrent mark sweep GC freed 75509(5MB) AllocSpace objects, 178(3MB) LOS objects, 30% free, 36MB/52MB, paused 1.763ms total 184.710ms
D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  834): mCursor = null
,E/SMD     (  285): DCD ON
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 39
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 1050s ago
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,E/SMD     (  285): DCD ON
,I/MotionRecognitionService(  834): setPowerConnected  = true,
D/BatteryService(  834): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :8
,V/AlarmManager(  834): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): stay LED for fully charged
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7416): Starting books sync, d
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1718): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7416): null auth token
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,I/qtaguid ( 7416): Untagging socket 34
,W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
,W/ApiaryClient( 7416): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8796964688650804568&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/TimaService(  834): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  834): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  834): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  834): User[0] Flushing usage stats to disk
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7416): null auth token
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,I/PhoneStatusBar( 1169): Icon Only
,I/qtaguid ( 7416): Tagging socket 41 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/ApplicationUsage(  834): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  834): Updating Usage Statistics in DB @ 1450234143787
,I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  834): 	,at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
,W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
,W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	,at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  834): 	,at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	,at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): ,	,at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
,W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350),
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): ,	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/System.err(  834): 	,at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
,W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	,at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	,at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	,at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134),
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	,at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	,at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
,W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350),
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): ,	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/qtaguid ( 7416): Untagging socket 34,
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference,
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304),
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102),
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
,W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
,W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/ApiaryClient( 7416): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8796964688650804568&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
,W/ApiaryClient( 7416): Headers suppressed
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304),
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102),
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): ,	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
,W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350),
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253),
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145),
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): ,	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	,at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	,at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'andr,oid.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  834): ::getAppControlDB: Exception to create DB
W/System.err(  834): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/Syste,m.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  834): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  834): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  834): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  834): Done Updating Usage Statistics in DB @ 1450234143907
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1718): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1718): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1718): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1718): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1718): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7416): Authentication error
E/BooksAccountManager( 7416): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7416): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7416): null auth token
,I/qtaguid ( 7416): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7416, getuid(): 10082
,I/qtaguid ( 7416): Untagging socket 34
,W/ApiaryClient( 7416): Error response from books API: {
W/ApiaryClient( 7416):  "error": {
W/ApiaryClient( 7416):   "errors": [
W/ApiaryClient( 7416):    {
W/ApiaryClient( 7416):     "domain": "global",
W/ApiaryClient( 7416):     "reason": "required",
W/ApiaryClient( 7416):     "message": "Login Required",
W/ApiaryClient( 7416):     "locationType": "header",
W/ApiaryClient( 7416):     "location": "Authorization"
W/ApiaryClient( 7416):    }
W/ApiaryClient( 7416):   ],
W/ApiaryClient( 7416):   "code": 401,
W/ApiaryClient( 7416):   "message": "Login Required"
W/ApiaryClient( 7416):  }
W/ApiaryClient( 7416): }
,W/ApiaryClient( 7416): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8796964688650804568&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7416): Headers suppressed
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  834): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel(  834): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  834): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  834): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,D/TimaService(  834): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/BooksSync( 7416): Soft error
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8796964688650804568&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7416): Headers suppressed
E/BooksSync( 7416): 
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7416): Sync error
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7416): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8796964688650804568&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7416): Headers suppressed
E/BooksSync( 7416): 
E/BooksSync( 7416): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7416): Finished books sync
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  834): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1188395, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  834): mCursor = null
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :4
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  834): stay LED for fully charged
D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 41
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :8
,V/AlarmManager(  834): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/HttpOperation( 6642): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at dsf.a(PG:807)
E/HttpOperation( 6642): 	at fhk.a(PG:1126)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 8 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 10 more
,I/art     ( 1169): Explicit concurrent mark sweep GC freed 91473(4MB) AllocSpace objects, 64(5MB) LOS objects, 30% free, 36MB/52MB, paused 893us total 92.028ms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6642): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at ieo.a(PG:43)
E/HttpOperation( 6642): 	at iep.a(PG:93)
E/HttpOperation( 6642): 	at fhn.a(PG:59)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
,E/ExperimentLoader( 6642): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): 	at kfv.a(PG:65)
E/ExperimentLoader( 6642): 	at kff.u(PG:385)
E/ExperimentLoader( 6642): 	at kfb.a(PG:29)
E/ExperimentLoader( 6642): 	at kff.l(PG:132)
E/ExperimentLoader( 6642): 	at ieo.a(PG:43)
E/ExperimentLoader( 6642): 	at iep.a(PG:93)
E/ExperimentLoader( 6642): 	at fhn.a(PG:59)
E/ExperimentLoader( 6642): 	at lex.a(PG:85)
E/ExperimentLoader( 6642): 	at lex.b(PG:132)
E/ExperimentLoader( 6642): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6642): 	at fhk.a(PG:908)
E/ExperimentLoader( 6642): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6642): 	at ihi.a(PG:22)
E/ExperimentLoader( 6642): 	at kft.a(PG:91)
E/ExperimentLoader( 6642): 	at kfv.a(PG:62)
E/ExperimentLoader( 6642): 	... 12 more
E/ExperimentLoader( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6642): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6642): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6642): 	at ihi.a(PG:19)
E/ExperimentLoader( 6642): 	... 14 more
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
E/SMD     (  285): DCD ON
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/HttpOperation( 6642): [getaccountstatus] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at ixd.a(PG:248)
E/HttpOperation( 6642): 	at ixd.b(PG:206)
E/HttpOperation( 6642): 	at ixd.a(PG:175)
E/HttpOperation( 6642): 	at fig.a(PG:78)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/EsSyncAdapterService( 6642): Sync failure
E/EsSyncAdapterService( 6642): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6642): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6642): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6642): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6642): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6642): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6642): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6642): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6642): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6642): 	... 10 more
E/EsSyncAdapterService( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6642): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6642): 	... 12 more
E/EsSyncAdapterService( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6642): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6642): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6642): 	... 14 more
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  834): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 1243239, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  834): mCursor = null
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 42
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 1155s ago
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :4
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/BatteryService(  834): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 43
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :8
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 44
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,D/BatteryService(  834): stay LED for fully charged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  834): !@Sync 45
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 46
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  834): stay LED for fully charged
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6642): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at dsf.a(PG:807)
E/HttpOperation( 6642): 	at fhk.a(PG:1126)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 8 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 10 more
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6642): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at ieo.a(PG:43)
E/HttpOperation( 6642): 	at iep.a(PG:93)
E/HttpOperation( 6642): 	at fhn.a(PG:59)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
,E/ExperimentLoader( 6642): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): 	at kfv.a(PG:65)
E/ExperimentLoader( 6642): 	at kff.u(PG:385)
E/ExperimentLoader( 6642): 	at kfb.a(PG:29)
E/ExperimentLoader( 6642): 	at kff.l(PG:132)
E/ExperimentLoader( 6642): 	at ieo.a(PG:43)
E/ExperimentLoader( 6642): 	at iep.a(PG:93)
E/ExperimentLoader( 6642): 	at fhn.a(PG:59)
E/ExperimentLoader( 6642): 	at lex.a(PG:85)
E/ExperimentLoader( 6642): 	at lex.b(PG:132)
E/ExperimentLoader( 6642): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6642): 	at fhk.a(PG:908)
E/ExperimentLoader( 6642): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6642): 	at ihi.a(PG:22)
E/ExperimentLoader( 6642): 	at kft.a(PG:91)
E/ExperimentLoader( 6642): 	at kfv.a(PG:62)
E/ExperimentLoader( 6642): 	... 12 more
E/ExperimentLoader( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6642): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6642): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6642): 	at ihi.a(PG:19)
E/ExperimentLoader( 6642): 	... 14 more
,I/art     ( 1718): Explicit concurrent mark sweep GC freed 38879(2MB) AllocSpace objects, 30(2MB) LOS objects, 39% free, 18MB/30MB, paused 2.201ms total 112.248ms
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1718): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6642): [getaccountstatus] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at ixd.a(PG:248)
E/HttpOperation( 6642): 	at ixd.b(PG:206)
E/HttpOperation( 6642): 	at ixd.a(PG:175)
E/HttpOperation( 6642): 	at fig.a(PG:78)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
,E/EsSyncAdapterService( 6642): Sync failure
E/EsSyncAdapterService( 6642): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6642): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6642): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6642): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6642): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6642): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6642): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6642): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6642): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6642): 	... 10 more
E/EsSyncAdapterService( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6642): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6642): 	... 12 more
E/EsSyncAdapterService( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6642): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6642): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6642): 	... 14 more
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  834): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 1396755, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  834): mCursor = null
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 1265s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,D/BatteryService(  834): stay LED for fully charged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 47
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :4
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  834): stay LED for fully charged
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :8
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/BatteryService(  834): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 48
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 49
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3223): Disconnected process message: 10
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,D/BatteryService(  834): stay LED for fully charged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/TimaService(  834): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  834): TimaServiceHandler.handleMessage what =1
,D/TimaService(  834): TIMA: checkEvent, operation: 50000 subject: 10000
,E/Watchdog(  834): !@Sync 50
,E/SMD     (  285): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  834): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  834): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  834): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  834): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 1380s ago
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,D/BatteryService(  834): stay LED for fully charged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 51
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,E/SMD     (  285): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 52
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,D/BatteryService(  834): stay LED for fully charged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 53
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 54
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 1500s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6642): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at dsf.a(PG:807)
E/HttpOperation( 6642): 	at fhk.a(PG:1126)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 8 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 10 more
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
,D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
E/HttpOperation( 6642): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at kff.l(PG:132)
E/HttpOperation( 6642): 	at ieo.a(PG:43)
E/HttpOperation( 6642): 	at iep.a(PG:93)
E/HttpOperation( 6642): 	at fhn.a(PG:59)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
E/ExperimentLoader( 6642): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6642): 	at kfv.a(PG:65)
E/ExperimentLoader( 6642): 	at kff.u(PG:385)
E/ExperimentLoader( 6642): 	at kfb.a(PG:29)
E/ExperimentLoader( 6642): 	at kff.l(PG:132)
E/ExperimentLoader( 6642): 	at ieo.a(PG:43)
E/ExperimentLoader( 6642): 	at iep.a(PG:93)
E/ExperimentLoader( 6642): 	at fhn.a(PG:59)
E/ExperimentLoader( 6642): 	at lex.a(PG:85)
E/ExperimentLoader( 6642): 	at lex.b(PG:132)
E/ExperimentLoader( 6642): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6642): 	at fhk.a(PG:908)
E/ExperimentLoader( 6642): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6642): 	at ihi.a(PG:22)
E/ExperimentLoader( 6642): 	at kft.a(PG:91)
E/ExperimentLoader( 6642): 	at kfv.a(PG:62)
E/ExperimentLoader( 6642): 	... 12 more
E/ExperimentLoader( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6642): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6642): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6642): 	at ihi.a(PG:19)
E/ExperimentLoader( 6642): 	... 14 more
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1718): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1718): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1718): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1718): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1718): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  834): uri = 14 selection = getSealedState
,D/SecContentProvider2(  834): mCursor = null
D/SecContentProvider2(  834): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  834): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  834): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6642): [getaccountstatus] Unexpected exception
E/HttpOperation( 6642): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6642): 	at kfv.a(PG:65)
E/HttpOperation( 6642): 	at kff.u(PG:385)
E/HttpOperation( 6642): 	at kfb.a(PG:29)
E/HttpOperation( 6642): 	at ixd.a(PG:248)
E/HttpOperation( 6642): 	at ixd.b(PG:206)
E/HttpOperation( 6642): 	at ixd.a(PG:175)
E/HttpOperation( 6642): 	at fig.a(PG:78)
E/HttpOperation( 6642): 	at lex.a(PG:85)
E/HttpOperation( 6642): 	at lex.b(PG:132)
E/HttpOperation( 6642): 	at fhk.a(PG:1146)
E/HttpOperation( 6642): 	at fhk.a(PG:908)
E/HttpOperation( 6642): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6642): 	at ihi.a(PG:22)
E/HttpOperation( 6642): 	at kft.a(PG:91)
E/HttpOperation( 6642): 	at kfv.a(PG:62)
E/HttpOperation( 6642): 	... 12 more
E/HttpOperation( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6642): 	at gde.c(Unknown Source)
E/HttpOperation( 6642): 	at gde.b(Unknown Source)
E/HttpOperation( 6642): 	at ihi.a(PG:19)
E/HttpOperation( 6642): 	... 14 more
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
E/EsSyncAdapterService( 6642): Sync failure
E/EsSyncAdapterService( 6642): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6642): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6642): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6642): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6642): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6642): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6642): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6642): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6642): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6642): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6642): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6642): 	... 10 more
E/EsSyncAdapterService( 6642): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6642): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6642): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6642): 	... 12 more
E/EsSyncAdapterService( 6642): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6642): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6642): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6642): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6642): 	... 14 more
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  834): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 1649112, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  834): Explicit concurrent mark sweep GC freed 82029(6MB) AllocSpace objects, 162(3MB) LOS objects, 30% free, 36MB/52MB, paused 1.750ms total 165.105ms
D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  834): mCursor = null
,E/SQLiteLog( 1718): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 55
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  834): waitForAlarm result :4
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  834): stay LED for fully charged
D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  834): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 56
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 57
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 58
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 1625s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 59
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/NetworkStatsFactory(  834): UpdateStatsForKnox
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/BatteryService(  834): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService(  834): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  834): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  834): TimaServiceHandler.handleMessage what =1
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel(  834): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  834): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  834): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  834): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 61
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  834): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 62
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  834): Plugged
,I/MotionRecognitionService(  834): setPowerConnected  = true
,D/BatteryService(  834): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3223): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  834): [PWL] Off : 1755s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  834): !@Sync 63
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  834): SIOP:: AP = 280, PST = 288, CUR = 300
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8923): 
D/AndroidRuntime( 8923): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8923): CheckJNI is OFF
D/AndroidRuntime( 8923): setted country_code = Germany
D/AndroidRuntime( 8923): setted countryiso_code = DE
D/AndroidRuntime( 8923): setted sales_code = DBT
D/AndroidRuntime( 8923): readGMSProperty: start
D/AndroidRuntime( 8923): readGMSProperty: already setted!!
D/AndroidRuntime( 8923): readGMSProperty: end
D/AndroidRuntime( 8923): addProductProperty: start
E/AffinityControl( 8923): AffinityControl: registerfunction enter
D/AndroidRuntime( 8923): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  834): START PACKAGE DELETE: observer{563787629}
D/PackageManager(  834): pkg{<packageName>}
D/PackageManager(  834): user{0}
D/PackageManager(  834): caller{2000}
D/PackageManager(  834): flags{3}
D/PersonaManagerService(  834): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  834): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  834): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  834): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  834): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  834): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  834): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  834): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  834): getApplicationUninstallationEnabled
D/ApplicationPolicy(  834): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  834): !@killApplicatoin: 10367, uninstall pkg
I/ActivityManager(  834): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
I/ActivityManager(  834): Killing 7489:com.test.thalitest/u0a367 (adj 0): stop com.test.thalitest
I/ActivityManager(  834): Killing 7549:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1803s
I/ActivityManager(  834): Killing 7965:com.android.email/u0a163 (adj 15): empty for 1803s
E/SMD     (  285): DCD ON
I/ActivityManager(  834): Killing 7947:com.samsung.android.sconnect/u0a138 (adj 15): empty for 1803s
I/ActivityManager(  834): Killing 7883:com.google.android.apps.magazines/u0a128 (adj 15): empty for 1803s
I/ActivityManager(  834): Killing 7859:com.android.chrome/u0a88 (adj 15): empty for 1803s
I/ActivityManager(  834): Killing 6604:com.sec.chaton/u0a86 (adj 15): empty for 1803s
I/ActivityManager(  834): Killing 7829:com.sec.knox.bridge/1000 (adj 15): empty for 1803s
I/ActivityManager(  834): Killing 7317:com.sec.android.widgetapp.ap.hero.accuweather/u0a71 (adj 15): empty for 1803s
I/ActivityManager(  834): Killing 7795:com.osp.app.signin/u0a45 (adj 15): empty for 1803s
I/ActivityManager(  834): Killing 7750:com.policydm/1000 (adj 15): empty for 1803s
I/ActivityManager(  834): Killing 7731:com.sec.android.soagent/u0a37 (adj 15): empty for 1803s
I/ActivityManager(  834): Killing 7716:com.samsung.klmsagent/u0a19 (adj 15): empty for 1803s
I/ActivityManager(  834): Killing 7698:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1803s
I/ActivityManager(  834): Killing 7677:com.sec.android.diagmonagent/1000 (adj 15): empty for 1803s
I/ActivityManager(  834): Killing 7657:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1803s
I/ActivityManager(  834): Killing 6777:com.sec.pcw.device/1000 (adj 15): empty for 1803s
I/ActivityManager(  834): Killing 7990:com.sec.android.provider.badge/u0a78 (adj 15): empty for 1803s
I/ActivityManager(  834): Killing 7245:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): empty for 1811s
I/ActivityManager(  834): Killing 7385:com.sec.android.app.camera/u0a154 (adj 15): empty for 1828s
I/ActivityManager(  834): Killing 7366:com.sec.android.GeoLookout/u0a113 (adj 15): empty for 1828s
I/ActivityManager(  834): Killing 7349:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): empty for 1829s
I/ActivityManager(  834): Killing 7323:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): empty for 1829s
I/ActivityManager(  834): Killing 6835:com.android.mms/u0a50 (adj 15): empty for 1829s
I/ActivityManager(  834): Killing 5994:com.sec.android.gallery3d/u0a48 (adj 15): empty for 1829s
I/ActivityManager(  834): Killing 5035:com.android.defcontainer/u0a5 (adj 15): empty for 1837s
I/ActivityManager(  834): Killing 7163:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): empty for 1844s
I/ActivityManager(  834): Killing 6710:com.google.android.gms:car/u0a12 (adj 15): empty for 1844s
I/ActivityManager(  834): Killing 7146:com.sec.kidsplat.installer/u0a166 (adj 15): empty for 1845s
I/ActivityManager(  834): Killing 7108:com.samsung.helphub/1000 (adj 15): empty for 1845s
I/ActivityManager(  834):   Force finishing activity ActivityRecord{37aeb80 u0 com.test.thalitest/.MainActivity t11}
D/FocusedStackFrame(  834): Set to : 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/ProcessStatsService(  834): Prepared write state in 12ms
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  248): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
I/SurfaceFlinger(  248): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ConnectivityService(  834): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiService(  834): Client connection lost with reason: 4
W/PackageSettings(  834): Skipping PackageSetting{607c84d com.example.hello/10375} due to missing metadata
D/CountryDetector(  834): No listener is left
I/ProcessStatsService(  834): Pruning old procstats: /data/system/procstats/state-2015-12-15-15-43-11.bin
I/ActivityManager(  834): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/art     ( 1585): Explicit concurrent mark sweep GC freed 10095(686KB) AllocSpace objects, 1(39KB) LOS objects, 40% free, 16MB/27MB, paused 629us total 30.993ms
E/libprocessgroup(  834): failed to kill 1 processes for processgroup 7489
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
E/SamsungIME( 1867): mOCRHelper is null
D/ResourcesManager( 1489): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
W/ResourcesManager( 1489): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1489): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1489): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1489): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
W/GeofencerStateMachine( 2179): Ignoring removeGeofence because network location is disabled.
I/InputReader(  834): Reconfiguring input devices.  changes=0x00000010
W/ResourcesManager( 1489): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 1489): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8953): MountEmulatedStorage()
E/Zygote  ( 8953): v2
I/libpersona( 8953): KNOX_SDCARD checking this for 10019
I/libpersona( 8953): KNOX_SDCARD not a persona
I/art     ( 4571): Explicit concurrent mark sweep GC freed 4028(225KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 14MB/24MB, paused 14.525ms total 81.140ms
I/ActivityManager(  834): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8953 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
I/SELinux ( 8953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8953): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  834): Explicit concurrent mark sweep GC freed 32535(3MB) AllocSpace objects, 86(1526KB) LOS objects, 30% free, 36MB/52MB, paused 1.850ms total 176.842ms
I/art     (  834): WaitForGcToComplete blocked for 94.559ms for cause Explicit
D/ResourcesManager(  834): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/TimaKeyStoreProvider( 8953): TimaSignature is unavailable
D/ActivityThread( 8953): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/SecContentProvider2(  834): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  834): mCursor = null
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/SurfaceWidgetView( 1489): destroyHardwareResources():884048749
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
V/WindowOrientationListener(  834): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  834): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  834): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  834): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  834): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 8953): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/Launcher( 1489): onRestart, Launcher: 381940035
D/Launcher( 1489): onStart, Launcher: 381940035
D/Launcher.HomeView( 1489): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2264): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2264): [237392/6] SurfaceWidget drawing first frame
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  248): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/RegisteredServicesCache( 1468): empty dynamic service
D/StatusBarManagerService(  834): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBarManagerService(  834): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/art     ( 1818): Explicit concurrent mark sweep GC freed 4412(210KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 14MB/19MB, paused 453us total 47.211ms
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/KLMS-2.4.503: ( 8953): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.503: ( 8953): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1450234839832
I/KLMS-2.4.503: ( 8953): MainReciver(): PACKAGE_REMOVED
D/InputMethodManagerService(  834): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  834): Got RemoteException sending setActive(false) notification to pid 7489 uid 10367
W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/KLMS-2.4.503: ( 8953): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/EnterpriseDeviceManagerService(  834): Package has changed for user 0
D/EnterpriseDeviceManagerService(  834): Admin package name: com.google.android.gms
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Books/Books.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/Timeline(  834): Timeline: Activity_windows_visible id: ActivityRecord{c904fc9 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:1907921
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
I/art     (  834): Explicit concurrent mark sweep GC freed 10714(520KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 4.151ms total 271.251ms
W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
E/Zygote  ( 8974): MountEmulatedStorage()
E/Zygote  ( 8974): v2
I/libpersona( 8974): KNOX_SDCARD checking this for 10104
I/libpersona( 8974): KNOX_SDCARD not a persona
I/ActivityManager(  834): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8974 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/ActivityManager(  834): Killing 8019:com.samsung.android.service.travel/u0a178 (adj 15): empty for 1804s
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Videos/Videos.apk
W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/SELinux ( 8974): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8974): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8974): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8974): TimaSignature is unavailable
D/ActivityThread( 8974): Added TimaKeyStore provider
D/ResourcesManager( 8974): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/PackageManager(  834): delete codoeFile: 
D/ResourcesManager(  834): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/PackageManager(  834): result of delete: 1{563787629}
D/elm:14451( 8974): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8974): ELMEngine.ELMEngine( context ).
D/AndroidRuntime( 8923): Shutting down VM
D/elm:14451( 8974): MDMBridge.setEnterpriseBridge()
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/RCPManagerService(  834): PackageReceiver onReceive()
I/HarmonyEASService(  834): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/elm:14451( 8974): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
D/KnoxMUMContainerPolicy(  834): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/elm:14451( 8974): ElmAgentService : onCreate()
D/elm:14451( 8974): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
V/AlarmManager(  834): waitForAlarm result :4
D/elm:14451( 8974): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8974): MDMBridge.getInstance()
D/elm:14451( 8974): MDMBridge.getAllLicenseInfoFromSDK()
D/BackupManagerService(  834): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  834): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  834): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  834): uID is 10367
V/EnterpriseBillingPolicy(  834): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  834): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  834): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  834): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  834): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  834): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  834): getBillingProfileForVpnEngine - end - null
D/elm:14451( 8974): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
E/Zygote  ( 8990): MountEmulatedStorage()
E/Zygote  ( 8990): v2
I/libpersona( 8990): KNOX_SDCARD checking this for 10017
I/libpersona( 8990): KNOX_SDCARD not a persona
W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
I/ActivityManager(  834): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8990 uid=10017 gids={50017, 9997} abi=armeabi-v7a
D/TaskPersister(  834): removeObsoleteFile: deleting file=11_task.xml
D/TaskPersister(  834): removeObsoleteFile: deleting file=11_task_thumbnail.png
W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/SELinux ( 8990): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
I/SELinux ( 8990): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BatteryService(  834): level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  834): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
E/SELinux ( 8990): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BatteryService(  834): stay LED for fully charged
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
D/elm:14451( 8974): ElmAgentService : onDestroy().
I/ActivityManager(  834): Killing 7620:com.google.android.music:main/u0a126 (adj 15): empty for 1802s
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
D/BatteryService(  834): Sending ACTION_BATTERY_CHANGED.
D/MotionRecognitionService(  834):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  834): Plugged
I/MotionRecognitionService(  834): setPowerConnected  = true
W/ResourcesManager(  834): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  834): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  834): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3223): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3223): Disconnected process message: 10
D/TimaKeyStoreProvider( 8990): TimaSignature is unavailable
D/ActivityThread( 8990): Added TimaKeyStore provider
W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  834): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
D/ResourcesManager( 8990): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager(  834): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/ResourcesManager(  834): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8990): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8990): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8990): onReceive() : package name is not s health. Return !!!
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  834): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
E/Zygote  ( 9007): MountEmulatedStorage()
E/Zygote  ( 9007): v2
I/libpersona( 9007): KNOX_SDCARD checking this for 1000
I/libpersona( 9007): KNOX_SDCARD not a persona
W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
I/ActivityManager(  834): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=9007 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  834): Killing 4970:com.google.android.gms.wearable/u0a12 (adj 15): empty for 1802s
W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/Resources(  834): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  834): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
I/SELinux ( 9007): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 9007): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027

```
