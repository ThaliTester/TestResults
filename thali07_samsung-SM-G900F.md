#### Test 50650278352fc1f_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/GLSActivity( 1672): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1672): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1672): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1672): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7581): Authentication error
E/BooksAccountManager( 7581): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7581): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7581): null auth token
D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/qtaguid ( 7581): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
I/qtaguid ( 7581): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/qtaguid ( 7581): Untagging socket 34
W/ApiaryClient( 7581): Error response from books API: {
W/ApiaryClient( 7581):  "error": {
W/ApiaryClient( 7581):   "errors": [
W/ApiaryClient( 7581):    {
W/ApiaryClient( 7581):     "domain": "global",
W/ApiaryClient( 7581):     "reason": "required",
W/ApiaryClient( 7581):     "message": "Login Required",
W/ApiaryClient( 7581):     "locationType": "header",
W/ApiaryClient( 7581):     "location": "Authorization"
W/ApiaryClient( 7581):    }
W/ApiaryClient( 7581):   ],
W/ApiaryClient( 7581):   "code": 401,
W/ApiaryClient( 7581):   "message": "Login Required"
W/ApiaryClient( 7581):  }
W/ApiaryClient( 7581): }
W/ApiaryClient( 7581): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5538342228581014085&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7581): Headers suppressed
--------- beginning of system
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
D/AndroidRuntime( 7627): 
D/AndroidRuntime( 7627): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7627): CheckJNI is OFF
D/AndroidRuntime( 7627): setted country_code = Germany
D/AndroidRuntime( 7627): setted countryiso_code = DE
D/AndroidRuntime( 7627): setted sales_code = DBT
D/AndroidRuntime( 7627): readGMSProperty: start
D/AndroidRuntime( 7627): readGMSProperty: already setted!!
D/AndroidRuntime( 7627): readGMSProperty: end
D/AndroidRuntime( 7627): addProductProperty: start
E/SMD     (  289): DCD ON
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
E/AffinityControl( 7627): AffinityControl: registerfunction enter
D/AndroidRuntime( 7627): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  888): inState():  stateMachine is null !!
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  888): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  888): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  888): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  888): mDVFSHelper.acquire()
D/FocusedStackFrame(  888): Set to : 0
D/Launcher.HomeView( 1476): onPause
D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 7627): Shutting down VM
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/TaskCloserActivity( 7188): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/Zygote  ( 7649): MountEmulatedStorage()
E/Zygote  ( 7649): v2
I/libpersona( 7649): KNOX_SDCARD checking this for 10367
I/libpersona( 7649): KNOX_SDCARD not a persona
I/ActivityManager(  888): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7649 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7649): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7649): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7649): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/art     (  318): Explicit concurrent mark sweep GC freed 8738(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 465us total 15.653ms
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 284us total 12.813ms
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
D/TimaKeyStoreProvider( 7649): TimaSignature is unavailable
D/ActivityThread( 7649): Added TimaKeyStore provider
I/MicrophoneInputStream( 1557): mic_close gfk@4ad7b90
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 308us total 13.105ms
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowManager(  888): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  888): Display changed displayId=0
V/AudioPolicyManager(  294): stopInput() input 29
V/audio_hw_primary(  294): in_standby: enter
I/HotwordRecognitionRnr( 1557): Hotword detection finished
I/HotwordRecognitionRnr( 1557): Stopping hotword detection.
D/Launcher.HomeView( 1476): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2233): [237392/6] Surface widget pause on instance = 1
D/accuweather( 2233): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2233): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2233): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2233): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/SurfaceWidgetView( 1476): destroyHardwareResources():694399748
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/accuweather( 2233): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2233): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7649): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/audio_hw_primary(  294): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  294): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  294): disable_audio_route: reset mixer path: audio-record
D/audio_route(  294): ++++ audio_route_update_mixer ==============
D/audio_route(  294): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  294): Setting mixer control: value: 0
D/audio_route(  294): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  294): disable_audio_route: exit
V/audio_hw_primary(  294): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  294): ++++ audio_route_update_mixer ==============
D/audio_route(  294): Setting mixer control: DEC2 Volume
D/audio_route(  294): Setting mixer control: value: 0
D/audio_route(  294): Setting mixer control: SLIM TX7 MUX, value: 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/audio_route(  294): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  294): Setting mixer control: value: 0
D/LockPatternUtilsCache( 1170): value : false
D/audio_route(  294): Setting mixer control: DEC2 MUX, value: 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/Launcher( 1476): onTrimMemory. Level: 20
D/audio_route(  294): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  294): stop_input_stream: exit: status(0)
V/audio_hw_primary(  294): in_standby: exit:  status(0)
V/AudioPolicyManager(  294): releaseInput() 29
V/AudioPolicyManager(  294): closeInput(29)
D/SurfaceWidgetView( 1476): destroyHardwareResources():694399748
V/audio_hw_primary(  294): adev_close_input_stream
V/audio_hw_primary(  294): in_standby: enter
V/audio_hw_primary(  294): in_standby: exit:  status(0)
E/audio_hw_primary(  294): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  294): releaseInput() exit
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
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/WebViewFactory( 7649): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7649): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/LibraryLoader( 7649): Loading: webviewchromium
I/LibraryLoader( 7649): Time to load native libraries: 2 ms (timestamps 4981-4983)
I/LibraryLoader( 7649): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/WebViewChromiumFactoryProvider( 7649): Binding Chromium to main looper Looper (main, tid 1) {2a535547}
I/LibraryLoader( 7649): Expected native library version number "",actual native library version number ""
I/chromium( 7649): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7649): Initializing chromium process, renderers=0
W/art     ( 7649): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/chromium( 7649): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7649): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7649): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/Adreno-EGL( 7649): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7649): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7649): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7649): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7649): Remote Branch: 
I/Adreno-EGL( 7649): Local Patches: 
I/Adreno-EGL( 7649): Reconstruct Branch: 
V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
W/chromium( 7649): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/chromium( 7649): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/art     ( 7649): Attempt to remove local handle scope entry from IRT, ignoring
W/GLSActivity( 1672): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1672): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1672): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1672): 	at android.os.Binder.execTransact(Binder.java:446)
D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/AwContents( 7649): onDetachedFromWindow called when already detached. Ignoring
E/BooksAccountManager( 7581): Authentication error
E/BooksAccountManager( 7581): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7581): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7581): null auth token
I/qtaguid ( 7581): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/SystemWebViewEngine( 7649): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/art     ( 7649): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7649): Attempt to remove local handle scope entry from IRT, ignoring
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/qtaguid ( 7581): Untagging socket 34
W/ApiaryClient( 7581): Error response from books API: {
W/ApiaryClient( 7581):  "error": {
W/ApiaryClient( 7581):   "errors": [
W/ApiaryClient( 7581):    {
W/ApiaryClient( 7581):     "domain": "global",
W/ApiaryClient( 7581):     "reason": "required",
W/ApiaryClient( 7581):     "message": "Login Required",
W/ApiaryClient( 7581):     "locationType": "header",
W/ApiaryClient( 7581):     "location": "Authorization"
W/ApiaryClient( 7581):    }
W/ApiaryClient( 7581):   ],
W/ApiaryClient( 7581):   "code": 401,
W/ApiaryClient( 7581):   "message": "Login Required"
W/ApiaryClient( 7581):  }
W/ApiaryClient( 7581): }
W/ApiaryClient( 7581): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5538342228581014085&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7581): Headers suppressed
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/Activity( 7649): performCreate Call secproduct feature valuefalse
D/Activity( 7649): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7649): Render dirty regions requested: true
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ActivityManager(  888): post active user change for 0
D/KnoxTimeoutHandler(  888): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  888): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
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
I/OpenGLRenderer( 7649): Initialized EGL, version 1.4
I/OpenGLRenderer( 7649): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7649): Enabling debug mode 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/InputMethodManagerService(  888): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/ActivityManager(  888): Displayed com.test.thalitest/.MainActivity: +648ms
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/Timeline( 7649): Timeline: Activity_idle id: android.os.BinderProxy@23cd0f36 time:95367
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
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/JsMessageQueue( 7649): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/chromium( 7649): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7649): 
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
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
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (7/8)
I/SurfaceFlinger(  249): id=14 Removed Starting com.test.thalitest (-2/8)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/CustomFrequencyManagerService(  888): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  888): mDVFSHelper.release()
I/Timeline(  888): Timeline: Activity_windows_visible id: ActivityRecord{21e018a0 u0 com.test.thalitest/.MainActivity t11} time:95591
D/CustomFrequencyManagerService(  888): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  pkgName : ACTIVITY_RESUME_BOOSTER@10
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
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/jxcore_app_log( 7649): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358543744
D/JX-Cordova( 7649): jxcore cordova android initializing
E/Adreno-ES20( 7649): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7649): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  888): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/BooksSync( 7581): Soft error
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5538342228581014085&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7581): Headers suppressed
E/BooksSync( 7581): 
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7581): Sync error
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5538342228581014085&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7581): Headers suppressed
E/BooksSync( 7581): 
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7581): Finished books sync
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  888): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 67261, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  888): Killing 6534:com.sec.chaton/u0a86 (adj 15): bgCount ##41
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  888): mCursor = null
,W/libprocessgroup(  888): failed to open /acct/uid_10086/pid_6534/cgroup.procs: No such file or directory
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,W/jxcore-log( 7649): Initializing JXcore engine
,W/jxcore-log( 7649): JXcore engine is ready
,W/jxcore-log( 7649): Starting JXcore engine
,E/auditd  ( 2083): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  888): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  888): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,D/SecurityLogAgent( 7482):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7482):  SeDenialReceiver : File path = null
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,W/jxcore-log( 7649): Platform android
W/jxcore-log( 7649): 
W/jxcore-log( 7649): Process ARCH arm
W/jxcore-log( 7649): 
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
,I/GAV2    ( 7581): Thread[GAThread,5,main]: No campaign data found.
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/SMD     (  289): DCD ON
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7649): JXcore Cordova bridge is ready!
I/jxcore-log( 7649): 
W/jxcore-log( 7649): JXcore engine is started
,I/Choreographer( 7649): Skipped 122 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7649): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 7649): Error!: missing ) after argument list
E/jxcore  ( 7649): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
I/chromium( 7649): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame(  888): Set to : 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/PluginManager( 7649): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 46ms. Plugin should use CordovaInterface.getThreadPool().
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/CustomFrequencyManagerService(  888): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  888): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SQLiteSecureOpenHelper( 3527): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3527): getDatabaseLocked(b,b,pwd)...
,V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  888): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  888): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SurfaceWidgetView( 1476): destroyHardwareResources():694399748
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/Launcher( 1476): onRestart, Launcher: 220999577
,D/Launcher( 1476): onStart, Launcher: 220999577
D/Launcher.HomeView( 1476): onStart
,D/Launcher( 1476): onResume, Launcher: 220999577
,D/SettingsProvider(  888): name = kids_home_mode
D/SettingsProvider(  888): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  888): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  888): selectionArgs: false
D/SettingsProvider(  888): selectionArgs: 10008
D/SecContentProvider(  888): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  888): ret = -1
,D/Launcher.HomeView( 1476): onResume
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2233): [237392/6] Surface widget resume on instance = 1
,D/accuweather( 2233): [KK AccuPhone]>>> SWW:209 [0:0] [SWW] onResume : instance = 1
,D/Launcher( 1476): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/MenuAppsGridFragment( 1476): onResume
,D/ActivityManager(  888): handle home activity for 0
I/WallpaperManagerService(  888): switchPersonaWallpaper is called for personaId-0
D/ActivityManager(  888): post active user change for 0
D/KnoxTimeoutHandler(  888): postActiveUserChange for user 0
D/WallpaperManagerService(  888):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler(  888): handleActiveUserChange for user 0
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2233): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2233): [237392/6] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  249): id=16 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/GalleryCacheReady( 5871): Receive : home resume
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/Mms/UIEventReceiver( 6742): ui event
,D/Launcher( 1476): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/InputMethodManagerService(  888): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/accuweather( 2233): [KK AccuPhone]>>> RM:150 [0:0]  onFirstUpdate :: mFU = false
D/accuweather( 2233): [KK AccuPhone]>>> SWW:223 [0:0]  onResume :: isFirst = false, cnt = 0
,D/accuweather( 2233): [KK AccuPhone]>>> SWW:230 [0:0] onResume : size = 1
D/accuweather( 2233): [KK AccuPhone]>>> SWW:512 [0:0]  registerTTReceiver ! 
,D/accuweather( 2233): [KK AccuPhone]>>> WR:139 [0:0] onResume orientation = 1, from res = Port fHD
,D/accuweather( 2233): [KK AccuPhone]>>> SM:523 [0:0] onResume : false, rsStep = 2
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/BroadcastQueue(  888): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1476, uid=10008) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/IInputConnectionWrapper( 7649): showStatusIcon on inactive InputConnection
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/MicrophoneInputStream( 1557): mic_starting gfk@310763c1
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/HotwordRecognitionRnr( 1557): Starting hotword detection.
,V/AudioPolicyManager(  294): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager(  294): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  294): adev_open_input_stream: enter
E/audio_hw_primary(  294): adev_open_input_stream : jack_config 0
,E/audio_hw_primary(  294): can not make /data/snd/hal_input.pcm 
E/audio_hw_primary(  294): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  294): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  294): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  294): adev_open_input_stream: exit
,I/AudioFlinger(  294): AudioFlinger's thread 0xafe77000 ready to run
,V/audio_hw_primary(  294): in_standby: enter
V/audio_hw_primary(  294): in_standby: exit:  status(0)
,V/audio_hw_primary(  294): in_standby: enter
,V/audio_hw_primary(  294): in_standby: exit:  status(0)
I/EDMNativeHelperService(  888): isMicrophoneEnabled
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/Timeline( 1476): Timeline: Activity_idle id: android.os.BinderProxy@1dc1f08 time:98063
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/GeoLookout( 7305): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/AudioPolicyManager(  294): startInput() input 31
V/AudioPolicyManager(  294): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  294): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  294): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  294): DeviceVector::getDevicesFromType() for type 80000004 found 0xb295b3c0
,V/audio_hw_primary(  294): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  294): in_set_parameters: exit: status(11)
V/AudioPolicyManager(  294): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  294): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1557): mic_started gfk@310763c1
,D/GeoLookout( 7305): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/msm8974_platform(  294): platform_update_usecase_from_source: input source :6
V/audio_hw_primary(  294): start_input_stream: enter: usecase(7)
V/voice   (  294): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  294): start_input_stream: usecase(7)
D/PreProcess(  294): new SamsungRecord
D/PreProcess(  294): new NS
I/samsungRecord(  294): [samsungrecord] SamsungRecInit 
,I/samsungRecord(  294): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord(  294): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord(  294): 1
D/SamsungRecord_NS(  294): [SamsungRecord_NS] Init SR 16000
,D/SamsungRecord_NS(  294): [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
V/audio_hw_primary(  294): select_devices: ENTER
V/audio_hw_primary(  294): select_devices: usecase(normal)
V/audio_hw_primary(  294): select_devices: usecase(PCM_CAPTURE)
V/msm8974_platform(  294): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  294): get_INPUT_snd_device: check by Input_source(6)
,V/msm8974_platform(  294): platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  294): get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
V/msm8974_platform(  294): platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
D/audio_hw_primary(  294): select_devices: out_snd_device(0: dummy)
D/audio_hw_primary(  294): select_devices: in_snd_device(122: vr-main-mic)
D/ACDB-LOADER(  294): ACDB -> send_audio_cal, acdb_id = 53, path =  1
,D/ACDB-LOADER(  294): ACDB -> send_adm_topology
D/ACDB-LOADER(  294): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  294): ACDB -> send_asm_topology
D/ACDB-LOADER(  294): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  294): ACDB -> send_audtable
,D/ACDB-LOADER(  294): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/        (  294): ACDBFILE_MGR:Read the devices count as zero, please check the acdb file
D/ACDB-LOADER(  294): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  294): ACDB -> send_audvoltable
D/ACDB-LOADER(  294): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
,D/        (  294): ACDBFILE_MGR:Read the devices count as zero, please check the acdb file
D/        (  294): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  294): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  294): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  294): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  294): enable_snd_device: snd_device(122: vr-main-mic, vr-main-mic)
,D/audio_route(  294): ++++ audio_route_update_mixer ==============
D/audio_route(  294): Setting mixer control: DEC2 Volume
D/audio_route(  294): Setting mixer control: value: 106
D/GeoLookout( 7305): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/audio_route(  294): Setting mixer control: SLIM TX7 MUX, value: 9
,D/audio_route(  294): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  294): Setting mixer control: value: 1
,D/audio_route(  294): Setting mixer control: DEC2 MUX, value: 1
,D/audio_route(  294): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  294): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  294): enable_audio_route: apply mixer path: audio-record
D/audio_route(  294): ++++ audio_route_update_mixer ==============
D/audio_route(  294): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  294): Setting mixer control: value: 1
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/audio_route(  294): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  294): enable_audio_route: exit
V/audio_hw_primary(  294): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,D/LockPatternUtilsCache( 1170): value : false
,V/audio_hw_primary(  294): start_input_stream: exit
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/accuweather( 2233): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/accuweather( 2233): [KK AccuPhone]>>> SM:442 [0:0] updateView iSA = false, mCI = 0, mSL = null , cls = 0 , cls = 1
,D/accuweather( 2233): [KK AccuPhone]>>> SM:447 [0:0] bg transparency val = 0
,D/accuweather( 2233): [KK AccuPhone]>>> SM:679 [0:0] [sCCTZ] set default tZ
,D/accuweather( 2233): [KK AccuPhone]>>> SM:1044 [0:0] setLayoutContentEmptyMsg = 2131558522
,D/GeoLookout( 7305): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
D/accuweather( 2233): [KK AccuPhone]>>> U:1012 [0:0] icon = 99, isDay = true, type = 261
,D/accuweather( 2233): [KK AccuPhone]>>> U:1187 [0:0] resID = 2130837848
D/accuweather( 2233): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
D/GeoLookout( 7305): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 7305): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
D/GeoLookout( 7305): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
,D/GeoLookout( 7305): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/GeoLookout( 7305): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
,D/GeoLookout( 7305): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,D/GeoLookout( 7305): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
,D/GeoLookout( 7305): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
,D/GeoLookout( 7305): H: oG7yKmvlgCB+MeB9ScCFjVjhROowReQZ6uZ83+PHbxXxfrUuNQHmPlY4PsIKqeHXpHMfmw7BKa8EvZP1XFE95vEpSHlOxg9XQoR6KQvcMJUezCj+VlRSvYmiaFKv4yMdF9ANJ7ri8t1rvBR++sDAZA==
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/TaskCloserActivity( 7188): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SurfaceWidget.Renderer( 2233): [237392/6] SurfaceWidget drawing first frame
,D/accuweather( 2233): [KK AccuPhone]>>> SM:1072 [0:0] complete setLayoutContentEmptyMsg Content
,I/art     ( 1557): Background sticky concurrent mark sweep GC freed 42068(2MB) AllocSpace objects, 18(4MB) LOS objects, 28% free, 16MB/23MB, paused 837us total 152.979ms
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/HotwordWorker( 1557): onReady
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/SurfaceWidget.Renderer( 2233): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2233): [237392/6] SurfaceWidget drawing first frame
D/SurfaceWidget.Renderer( 2233): [237392/6] SurfaceWidget drawing first frame
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SurfaceWidget.Renderer( 2233): [237392/6] SurfaceWidget drawing first frame
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/CustomFrequencyManagerService(  888): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  888): mDVFSHelper.release()
I/Timeline(  888): Timeline: Activity_windows_visible id: ActivityRecord{2982441c u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:98339
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/ActivityManager(  888): Killing 6845:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,D/CustomFrequencyManagerService(  888): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,W/ScreenOrientationListener( 7649): Removing an inexistent observer!
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
,W/libprocessgroup(  888): failed to open /acct/uid_10098/pid_6845/cgroup.procs: No such file or directory
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/PowerManagerService(  888): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1170 (0x0)
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
I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (7/8)
I/SurfaceFlinger(  249): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/CustomFrequencyManagerService(  888): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 888  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  888): SIOP:: AP = 400, PST = 431, CUR = 300
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/SMD     (  289): DCD ON
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  888): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  888): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  888): lcd : 5 +
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,D/lights  (  888): lcd : 5 -
,D/lights  (  888): lcd : 1 +
,D/lights  (  888): lcd : 1 -
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/SMD     (  289): DCD ON
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/Watchdog(  888): !@Sync 3
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,V/AlarmManager(  888): waitForAlarm result :4
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6569): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6569): [1] 5.onFinished: Scheduling replication attempt 2.
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  888): CMD_RSSI_POLL : out!
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/SMD     (  289): DCD ON
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Atfwd_Sendcmd(  343): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  343): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
,D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  888): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  888): Nap time (uid 1000)...
,I/PowerManagerService(  888): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  888): Going to sleep due to screen timeout (uid 1000)...
,D/InputManager-JNI(  888): setDeviceInteractive: 0
D/PowerManagerService(  888): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  888): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService(  888): handleSandman : startDream()
,D/InputManager-JNI(  888): sysfs_write +: /sys/class/input/event2/device/enabled: 0
E/PowerManagerService(  888): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  888): Sleeping (uid 1000)...
D/PowerManagerService(  888): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  888): [input device light] setInputDeviceLightOn is called : 0
I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),2 flag=404, ColorFade
D/InputManager-JNI(  888): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/PowerManagerService(  888): [input device light] handleInputDeviceLightOff
D/InputManager-JNI(  888): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/InputManager-JNI(  888): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService(  888): 	.unregisterCallback : 1, client=
D/SContextService(  888): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@de859e4, Service = Auto Rotation, used = 1
W/CAE     (  888): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  888): stop(ContextProvider.java:149)
V/CAE     (  888): clear(AutoRotationRunner.java:182)
V/CAE     (  888): disable(AutoRotationRunner.java:171)
,I/CAE     (  888): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  888): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  300): sendContextData: -78, 7, 0, 0
,D/CAE     (  888): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  888): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  888): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  888): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  888): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  888): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  888): removeSContextService() : service = Auto Rotation
D/SContextService(  888): ===== SContext Service List =====
D/SContextManager(  888):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@31b67311, service=Auto Rotation
,D/KeyguardViewMediator( 1170): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1170): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1170): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1170): notifyScreenOffLocked
,D/DisplayPowerController(  888): ColorFade: onAnimationStart
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/KeyguardViewMediator( 1170): timeout : 5000
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/Launcher.HomeView( 1476): onPause
,D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
,D/lights  (  888): lcd : 0 +
,D/DisplayPowerController(  888): getFinalBrightness : 8 -> 0
,D/lights  (  888): lcd : 0 -
,E/LightSensor(  888): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  888): mCallbacks.updateBrightness()
D/DisplayPowerController(  888): getFinalBrightness : 8 -> 0
,D/KeyguardViewMediator( 1170): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1170): handleNotifyScreenOff
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/TaskCloserActivity( 7188): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/StatusBarManagerService(  888): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LightsService(  888): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 888) 
,D/LightsService(  888): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  888): [SvcLED]  onSensorChanged::light value = 0
,D/Launcher.HomeView( 1476): onStop
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2233): [237392/6] Surface widget pause on instance = 1
,D/SensorManager(  888): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  888): unregisterListener ::   
,D/lights  (  888): led_pattern : 5 +
,D/accuweather( 2233): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
,D/accuweather( 2233): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2233): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
,D/BatteryService(  888): turn on LED for fully charged
,I/MicrophoneInputStream( 1557): mic_close gfk@310763c1
,D/accuweather( 2233): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2233): [KK AccuPhone]>>> SM:538 [0:0] onPause
,D/lights  (  888): led_pattern : 5 -
,D/LightsService(  888): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/AudioPolicyManager(  294): stopInput() input 31
,V/AudioPolicyManager(  294): releaseInput() 31
V/AudioPolicyManager(  294): closeInput(31)
,I/CAE     (  888): handleMessage(CaPowerManager.java:182) - AP_SLEEP
I/CAE     (  888): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
,I/CAE     (  888): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  888): SendSensorHubData: send data = -76, 13, -46, 0
,V/audio_hw_primary(  294): in_standby: enter
D/Sensorhubs(  300): sendContextData: -76, 13, -46, 0
,I/HotwordRecognitionRnr( 1557): Hotword detection finished
,I/HotwordRecognitionRnr( 1557): Stopping hotword detection.
,I/CAE     (  888): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 15, 28, 23,
,D/SensorHubManager(  888): SendSensorHubData: send data = -63, 14, 15, 28, 23
D/Sensorhubs(  300): sendContextData: -63, 14, 15, 28, 23
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  888):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  888): backgroundScan enabled=false startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  888): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  888): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  888): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
D/NotificationService(  888): ACTION_SCREEN_OFF
D/LightsService(  888): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 888) 
D/LightsService(  888): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
E/native  (  888): do suspend true
,D/LightsService(  888): [SvcLED]  onSensorChanged::light value = 0
,V/audio_hw_primary(  294): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  294): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  294): disable_audio_route: reset mixer path: audio-record
D/audio_route(  294): ++++ audio_route_update_mixer ==============
D/audio_route(  294): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  294): Setting mixer control: value: 0
,D/SensorManager(  888): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/audio_route(  294): ------ audio_route_update_mixer ==============
D/SensorManager(  888): unregisterListener ::   
D/LightsService(  888): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
V/audio_hw_primary(  294): disable_audio_route: exit
,V/audio_hw_primary(  294): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  294): ++++ audio_route_update_mixer ==============
D/audio_route(  294): Setting mixer control: DEC2 Volume
D/audio_route(  294): Setting mixer control: value: 0
D/audio_route(  294): Setting mixer control: SLIM TX7 MUX, value: 0
,D/audio_route(  294): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  294): Setting mixer control: value: 0
,D/audio_route(  294): Setting mixer control: DEC2 MUX, value: 0
,D/audio_route(  294): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  294): stop_input_stream: exit: status(0)
V/audio_hw_primary(  294): in_standby: exit:  status(0)
,V/audio_hw_primary(  294): adev_close_input_stream
V/audio_hw_primary(  294): in_standby: enter
V/audio_hw_primary(  294): in_standby: exit:  status(0)
E/audio_hw_primary(  294): adev_close_input_stream, set jack_in to null
,V/AudioPolicyManager(  294): releaseInput() exit
,D/audio_hw_primary(  294): adev_set_parameters: enter: screen_state=off
V/voice   (  294): voice_set_parameters: enter: screen_state=off
V/voice   (  294): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  294): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  294): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  294): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  294): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  888): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/DisplayPowerState(  888): !@ ColorFade entry
,D/DisplayPowerController(  888): ColorFade: onAnimationEnd
,D/IpRemoteDisplayController(  888): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  888): Bridge Server is not available
D/AutomaticBrightnessController(  888): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  888): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  888): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController(  888): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  888): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,D/SensorManager(  888): unregisterListener ::   
,E/Sensors (  888): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  888): unregisterListener ::   
,D/DisplayPowerController(  888): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  888): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  888): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  888): Display changed displayId=0
,D/VolumePanel( 1170): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1170): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
,D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,D/VolumePanel( 1170): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1170): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PersonaManagerService(  888): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  888): MSG_ACTION_SCREEN_OFF called
,D/StatusBar.NetworkController( 1170): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/NfcService( 1456): call the applyRotuiing
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/STATUSBAR-PhoneStatusBar( 1170):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1170): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1170): dismissHelpPopup 
,D/accuweather( 2233): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2233): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2233): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PowerManagerService(  888): [PWL] sb release: PowerManagerService.Broadcasts
,I/rmt_storage(  277): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
,I/rmt_storage(  277): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  277): wakelock acquired: 1, error no: 42
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
,D/SSRM:m  (  888): SIOP:: AP = 350, PST = 423, CUR = 300
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 22
I/rmt_storage(  277): 
,I/rmt_storage(  277): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
D/SurfaceControl(  888): Excessive delay in setPowerMode(): 260ms
D/PowerManagerService(  888): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  888): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  888): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  888): Got set_interactive hint
,I/PowerManagerService(  888): [PWL] Off : 0s ago
I/PowerManagerService(  888): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  888): [PWL]     mDisplayReady : false
,D/DisplayPowerController(  888): getFinalBrightness : 0 -> 0
D/PowerManagerService(  888): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  888): [PWL] sb release: PowerManagerService.Display
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,D/FactoryTest( 6351): Not factory mode
,D/FactoryTest( 6351): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6351): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6351): still no open session command from host, so toast
,W/ContextImpl( 6351): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6351): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6351): Timeline: Activity_launch_request id:com.android.settings time:113361
,E/PersonaManagerService(  888): inState():  stateMachine is null !!
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  888): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  888): mDVFSHelper.acquire()
,D/FocusedStackFrame(  888): Set to : 0
,V/ActivityManager(  888): Display changed displayId=0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
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
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,E/MTPRx   ( 6351): started activity for popup
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/SQLiteSecureOpenHelper( 3527): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3527): getDatabaseLocked(b,b,pwd)...
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardViewMediator( 1170): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/KeyguardViewMediator( 1170): doKeyguard: not showing because lockscreen is off
D/ResourcesManager( 6351): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6351): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6351): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6351): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6351): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6351): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6351): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6351): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6351): PREF_DONT_ASK_AGAIN : true
,D/FocusedStackFrame(  888): Set to : 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/InputMethodManagerService(  888): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  888): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@22abdbbc attribute=android.view.inputmethod.EditorInfo@f880745, token = android.os.BinderProxy@281c707b
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6351): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6351): dev.kiessupport is : TRUE
,D/Activity( 6351): performCreate Call secproduct feature valuefalse
,D/Activity( 6351): performCreate Call debug elastic valuetrue
,I/PowerManagerService(  888): [PWL] Off : 5s ago
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,W/ActivityManager(  888): mDVFSHelper.release()
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :8
,D/SSRM:m  (  888): SIOP:: AP = 340, PST = 410, CUR = 300
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  888): stay LED for fully charged
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1672): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
,D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Search.LoginHelper( 1557): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,D/ConnectivityService(  888): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  888): [PWL] Off : 15s ago
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,V/AlarmManager(  888): waitForAlarm result :4
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6569): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6569): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON,
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  888): SIOP:: AP = 330, PST = 395, CUR = 300
,D/X       (  888): broadcastSiopLevelIntent:: currentSiopLevel = -1
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,D/ContentApp( 1225):  LEVEL : -1
,E/Zygote  ( 7855): MountEmulatedStorage()
,E/Zygote  ( 7855): v2
,I/libpersona( 7855): KNOX_SDCARD checking this for 10054
I/libpersona( 7855): KNOX_SDCARD not a persona
,I/ActivityManager(  888): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=7855 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 7855): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7855): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7855): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7855): TimaSignature is unavailable
,D/ActivityThread( 7855): Added TimaKeyStore provider
,D/ResourcesManager( 7855): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7855): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7855): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7855): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7855): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 7855): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 7855): core_num = 4
,W/linker  ( 7855): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 7855): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 7855): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
D/videowall-Global( 7855): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 7855):  SIOP_LEVEL: -1
,I/ActivityManager(  888): Killing 6905:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,W/libprocessgroup(  888): failed to open /acct/uid_10033/pid_6905/cgroup.procs: No such file or directory
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 4
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/PowerManagerService(  888): [PWL] Off : 30s ago
,D/SSRM:m  (  888): SIOP:: AP = 320, PST = 379, CUR = 300
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  888): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  888): stay LED for fully charged
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6569): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6569): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SQLiteLog( 1672): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 320, PST = 366, CUR = 300
,E/SMD     (  289): DCD ON,
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 5279): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5279): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5279): 	at kfv.a(PG:65)
E/HttpOperation( 5279): 	at kff.u(PG:385)
E/HttpOperation( 5279): 	at kfb.a(PG:29)
E/HttpOperation( 5279): 	at kff.l(PG:132)
E/HttpOperation( 5279): 	at dsf.a(PG:807)
E/HttpOperation( 5279): 	at fhk.a(PG:1126)
E/HttpOperation( 5279): 	at fhk.a(PG:908)
E/HttpOperation( 5279): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5279): 	at ihi.a(PG:22)
E/HttpOperation( 5279): 	at kft.a(PG:91)
E/HttpOperation( 5279): 	at kfv.a(PG:62)
E/HttpOperation( 5279): 	... 8 more
E/HttpOperation( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5279): 	at gde.c(Unknown Source)
E/HttpOperation( 5279): 	at gde.b(Unknown Source)
E/HttpOperation( 5279): 	at ihi.a(PG:19)
E/HttpOperation( 5279): 	... 10 more
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
,D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 5279): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 5279): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5279): 	at kfv.a(PG:65)
E/HttpOperation( 5279): 	at kff.u(PG:385)
E/HttpOperation( 5279): 	at kfb.a(PG:29)
E/HttpOperation( 5279): 	at kff.l(PG:132)
E/HttpOperation( 5279): 	at ieo.a(PG:43)
E/HttpOperation( 5279): 	at iep.a(PG:93)
E/HttpOperation( 5279): 	at fhn.a(PG:59)
E/HttpOperation( 5279): 	at lex.a(PG:85)
E/HttpOperation( 5279): 	at lex.b(PG:132)
E/HttpOperation( 5279): 	at fhk.a(PG:1146)
E/HttpOperation( 5279): 	at fhk.a(PG:908)
E/HttpOperation( 5279): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5279): 	at ihi.a(PG:22)
E/HttpOperation( 5279): 	at kft.a(PG:91)
E/HttpOperation( 5279): 	at kfv.a(PG:62)
E/HttpOperation( 5279): 	... 12 more
E/HttpOperation( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5279): 	at gde.c(Unknown Source)
E/HttpOperation( 5279): 	at gde.b(Unknown Source)
E/HttpOperation( 5279): 	at ihi.a(PG:19)
E/HttpOperation( 5279): 	... 14 more
,E/ExperimentLoader( 5279): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5279): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5279): 	at kfv.a(PG:65)
E/ExperimentLoader( 5279): 	at kff.u(PG:385)
E/ExperimentLoader( 5279): 	at kfb.a(PG:29)
E/ExperimentLoader( 5279): 	at kff.l(PG:132)
E/ExperimentLoader( 5279): 	at ieo.a(PG:43)
E/ExperimentLoader( 5279): 	at iep.a(PG:93)
E/ExperimentLoader( 5279): 	at fhn.a(PG:59)
E/ExperimentLoader( 5279): 	at lex.a(PG:85)
E/ExperimentLoader( 5279): 	at lex.b(PG:132)
E/ExperimentLoader( 5279): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5279): 	at fhk.a(PG:908)
E/ExperimentLoader( 5279): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5279): 	at ihi.a(PG:22)
E/ExperimentLoader( 5279): 	at kft.a(PG:91)
E/ExperimentLoader( 5279): 	at kfv.a(PG:62)
E/ExperimentLoader( 5279): 	... 12 more
E/ExperimentLoader( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5279): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5279): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5279): 	at ihi.a(PG:19)
E/ExperimentLoader( 5279): 	... 14 more
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 1672): (10) POSIX Error : 11 SQLite Error : 3850
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): stay LED for fully charged
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3232): Disconnected process message: 10
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5279): [getaccountstatus] Unexpected exception
E/HttpOperation( 5279): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5279): 	at kfv.a(PG:65)
E/HttpOperation( 5279): 	at kff.u(PG:385)
E/HttpOperation( 5279): 	at kfb.a(PG:29)
E/HttpOperation( 5279): 	at ixd.a(PG:248)
E/HttpOperation( 5279): 	at ixd.b(PG:206)
E/HttpOperation( 5279): 	at ixd.a(PG:175)
E/HttpOperation( 5279): 	at fig.a(PG:78)
E/HttpOperation( 5279): 	at lex.a(PG:85)
E/HttpOperation( 5279): 	at lex.b(PG:132)
E/HttpOperation( 5279): 	at fhk.a(PG:1146)
E/HttpOperation( 5279): 	at fhk.a(PG:908)
E/HttpOperation( 5279): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5279): 	at ihi.a(PG:22)
E/HttpOperation( 5279): 	at kft.a(PG:91)
E/HttpOperation( 5279): 	at kfv.a(PG:62)
E/HttpOperation( 5279): 	... 12 more
E/HttpOperation( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5279): 	at gde.c(Unknown Source)
E/HttpOperation( 5279): 	at gde.b(Unknown Source)
E/HttpOperation( 5279): 	at ihi.a(PG:19)
E/HttpOperation( 5279): 	... 14 more
,E/EsSyncAdapterService( 5279): Sync failure
E/EsSyncAdapterService( 5279): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5279): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5279): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5279): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5279): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5279): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5279): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5279): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5279): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5279): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5279): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5279): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5279): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5279): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5279): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5279): 	... 10 more
E/EsSyncAdapterService( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5279): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5279): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5279): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5279): 	... 12 more
E/EsSyncAdapterService( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5279): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5279): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5279): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5279): 	... 14 more
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  888): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 155470, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  888): Explicit concurrent mark sweep GC freed 63289(3MB) AllocSpace objects, 30(2MB) LOS objects, 29% free, 37MB/53MB, paused 1.837ms total 319.116ms
,D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  888): mCursor = null
,E/SQLiteLog( 1672): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/PowerManagerService(  888): [PWL] Off : 50s ago
,D/SSRM:m  (  888): SIOP:: AP = 310, PST = 356, CUR = 300
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 5
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 310, PST = 346, CUR = 300
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,I/VacuumService( 1672): Vacuum at: now=1449588573618 tag=VacuumService
,I/GoogleURLConnFactory( 1672): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1672): Explicit concurrent mark sweep GC freed 43483(2MB) AllocSpace objects, 23(1863KB) LOS objects, 40% free, 17MB/29MB, paused 1.689ms total 115.760ms
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/Uploader( 1672): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1672): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1672): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1672): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1672): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1672): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1672): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1672): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1672): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1672): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1672): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1672): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1672): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,I/System.out( 1672): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1672): (HTTPLog)-Static: isShipBuild true
I/System.out( 1672): (HTTPLog)-Thread-198-488341560: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1672): Tagging socket 45 with tag 120100000000{4609,0} uid -1, pid: 1672, getuid(): 10012
,D/SSRM:m  (  888): SIOP:: AP = 310, PST = 337, CUR = 300
,I/qtaguid ( 1672): Tagging socket 61 with tag 120100000000{4609,0} uid -1, pid: 1672, getuid(): 10012
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6569): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6569): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Uploader( 1672): No account for auth token provided
,I/qtaguid ( 1672): Tagging socket 45 with tag 120100000000{4609,0} uid -1, pid: 1672, getuid(): 10012
,W/Uploader( 1672): No account for auth token provided
,I/qtaguid ( 1672): Tagging socket 45 with tag 120100000000{4609,0} uid -1, pid: 1672, getuid(): 10012
,W/Uploader( 1672): No account for auth token provided
,I/qtaguid ( 1672): Tagging socket 45 with tag 120100000000{4609,0} uid -1, pid: 1672, getuid(): 10012
,W/Uploader( 1672): No account for auth token provided
,I/qtaguid ( 1672): Tagging socket 45 with tag 120100000000{4609,0} uid -1, pid: 1672, getuid(): 10012
,W/Uploader( 1672): No account for auth token provided
,I/qtaguid ( 1672): Tagging socket 45 with tag 120100000000{4609,0} uid -1, pid: 1672, getuid(): 10012
,W/Uploader( 1672):  no longer exists, so no auth token.
,I/qtaguid ( 1672): Tagging socket 45 with tag 120100000000{4609,0} uid -1, pid: 1672, getuid(): 10012
,E/SQLiteLog( 1672): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/PowerManagerService(  888): [PWL] Off : 75s ago
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,V/AlarmManager(  888): waitForAlarm result :4
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7581): Starting books sync, d
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,D/ResourcesManager( 1672): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1672): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1672): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1672): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1672): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7581): Authentication error
E/BooksAccountManager( 7581): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7581): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7581): null auth token
,I/qtaguid ( 7581): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,I/qtaguid ( 7581): Untagging socket 34
,W/ApiaryClient( 7581): Error response from books API: {
W/ApiaryClient( 7581):  "error": {
W/ApiaryClient( 7581):   "errors": [
W/ApiaryClient( 7581):    {
W/ApiaryClient( 7581):     "domain": "global",
W/ApiaryClient( 7581):     "reason": "required",
W/ApiaryClient( 7581):     "message": "Login Required",
W/ApiaryClient( 7581):     "locationType": "header",
W/ApiaryClient( 7581):     "location": "Authorization"
W/ApiaryClient( 7581):    }
W/ApiaryClient( 7581):   ],
W/ApiaryClient( 7581):   "code": 401,
W/ApiaryClient( 7581):   "message": "Login Required"
W/ApiaryClient( 7581):  }
W/ApiaryClient( 7581): }
,W/ApiaryClient( 7581): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1302679129102012411&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7581): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1672): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1672): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1672): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1672): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7581): Authentication error
E/BooksAccountManager( 7581): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7581): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7581): null auth token
,I/qtaguid ( 7581): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
,I/qtaguid ( 7581): Untagging socket 34
,W/ApiaryClient( 7581): Error response from books API: {
W/ApiaryClient( 7581):  "error": {
W/ApiaryClient( 7581):   "errors": [
W/ApiaryClient( 7581):    {
W/ApiaryClient( 7581):     "domain": "global",
W/ApiaryClient( 7581):     "reason": "required",
W/ApiaryClient( 7581):     "message": "Login Required",
W/ApiaryClient( 7581):     "locationType": "header",
W/ApiaryClient( 7581):     "location": "Authorization"
W/ApiaryClient( 7581):    }
W/ApiaryClient( 7581):   ],
W/ApiaryClient( 7581):   "code": 401,
W/ApiaryClient( 7581):   "message": "Login Required"
W/ApiaryClient( 7581):  }
W/ApiaryClient( 7581): }
,W/ApiaryClient( 7581): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1302679129102012411&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7581): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 5
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1672): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1672): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1672): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1672): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7581): Authentication error
E/BooksAccountManager( 7581): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7581): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7581): null auth token
,I/qtaguid ( 7581): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
,I/qtaguid ( 7581): Untagging socket 34
,W/ApiaryClient( 7581): Error response from books API: {
W/ApiaryClient( 7581):  "error": {
W/ApiaryClient( 7581):   "errors": [
W/ApiaryClient( 7581):    {
W/ApiaryClient( 7581):     "domain": "global",
W/ApiaryClient( 7581):     "reason": "required",
W/ApiaryClient( 7581):     "message": "Login Required",
W/ApiaryClient( 7581):     "locationType": "header",
W/ApiaryClient( 7581):     "location": "Authorization"
W/ApiaryClient( 7581):    }
W/ApiaryClient( 7581):   ],
W/ApiaryClient( 7581):   "code": 401,
W/ApiaryClient( 7581):   "message": "Login Required"
W/ApiaryClient( 7581):  }
W/ApiaryClient( 7581): }
,W/ApiaryClient( 7581): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1302679129102012411&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7581): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  888): SIOP:: AP = 300, PST = 329, CUR = 300
,E/BooksSync( 7581): Soft error
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1302679129102012411&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7581): Headers suppressed
E/BooksSync( 7581): 
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7581): Sync error
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1302679129102012411&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7581): Headers suppressed
E/BooksSync( 7581): 
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7581): Finished books sync
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  888): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 160687, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  888): mCursor = null
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 6
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 300, PST = 319, CUR = 300,
,V/AlarmManager(  888): waitForAlarm result :4
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  888): stay LED for fully charged
D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6569): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6569): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 300, PST = 314, CUR = 300
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  343): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  343): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  888): [PWL] Off : 105s ago
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): stay LED for fully charged
D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 300, PST = 310, CUR = 300
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 7
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:m  (  888): SIOP:: AP = 300, PST = 307, CUR = 300
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 300, PST = 305, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/PowerManagerService(  888): [PWL] Off : 140s ago
,D/SSRM:m  (  888): SIOP:: AP = 300, PST = 303, CUR = 300
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 8
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 301, CUR = 300
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 299, CUR = 300
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 297, CUR = 300
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): stay LED for fully charged
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 1672): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5279): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5279): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5279): 	at kfv.a(PG:65)
E/HttpOperation( 5279): 	at kff.u(PG:385)
E/HttpOperation( 5279): 	at kfb.a(PG:29)
E/HttpOperation( 5279): 	at kff.l(PG:132)
E/HttpOperation( 5279): 	at dsf.a(PG:807)
E/HttpOperation( 5279): 	at fhk.a(PG:1126)
E/HttpOperation( 5279): 	at fhk.a(PG:908)
E/HttpOperation( 5279): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5279): 	at ihi.a(PG:22)
E/HttpOperation( 5279): 	at kft.a(PG:91)
E/HttpOperation( 5279): 	at kfv.a(PG:62)
E/HttpOperation( 5279): 	... 8 more
E/HttpOperation( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5279): 	at gde.c(Unknown Source)
E/HttpOperation( 5279): 	at gde.b(Unknown Source)
E/HttpOperation( 5279): 	at ihi.a(PG:19)
E/HttpOperation( 5279): 	... 10 more
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
,D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,E/HttpOperation( 5279): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5279): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5279): 	at kfv.a(PG:65)
E/HttpOperation( 5279): 	at kff.u(PG:385)
E/HttpOperation( 5279): 	at kfb.a(PG:29)
E/HttpOperation( 5279): 	at kff.l(PG:132)
E/HttpOperation( 5279): 	at ieo.a(PG:43)
E/HttpOperation( 5279): 	at iep.a(PG:93)
E/HttpOperation( 5279): 	at fhn.a(PG:59)
E/HttpOperation( 5279): 	at lex.a(PG:85)
E/HttpOperation( 5279): 	at lex.b(PG:132)
E/HttpOperation( 5279): 	at fhk.a(PG:1146)
E/HttpOperation( 5279): 	at fhk.a(PG:908)
E/HttpOperation( 5279): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5279): 	at ihi.a(PG:22)
E/HttpOperation( 5279): 	at kft.a(PG:91)
E/HttpOperation( 5279): 	at kfv.a(PG:62)
E/HttpOperation( 5279): 	... 12 more
E/HttpOperation( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5279): 	at gde.c(Unknown Source)
E/HttpOperation( 5279): 	at gde.b(Unknown Source)
E/HttpOperation( 5279): 	at ihi.a(PG:19)
E/HttpOperation( 5279): 	... 14 more
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/ExperimentLoader( 5279): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5279): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5279): 	at kfv.a(PG:65)
E/ExperimentLoader( 5279): 	at kff.u(PG:385)
E/ExperimentLoader( 5279): 	at kfb.a(PG:29)
E/ExperimentLoader( 5279): 	at kff.l(PG:132)
E/ExperimentLoader( 5279): 	at ieo.a(PG:43)
E/ExperimentLoader( 5279): 	at iep.a(PG:93)
E/ExperimentLoader( 5279): 	at fhn.a(PG:59)
E/ExperimentLoader( 5279): 	at lex.a(PG:85)
E/ExperimentLoader( 5279): 	at lex.b(PG:132)
E/ExperimentLoader( 5279): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5279): 	at fhk.a(PG:908)
E/ExperimentLoader( 5279): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5279): 	at ihi.a(PG:22)
E/ExperimentLoader( 5279): 	at kft.a(PG:91)
E/ExperimentLoader( 5279): 	at kfv.a(PG:62)
E/ExperimentLoader( 5279): 	... 12 more
E/ExperimentLoader( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5279): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5279): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5279): 	at ihi.a(PG:19)
E/ExperimentLoader( 5279): 	... 14 more
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,E/SQLiteLog( 1672): (10) POSIX Error : 11 SQLite Error : 3850
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
,D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5279): [getaccountstatus] Unexpected exception
E/HttpOperation( 5279): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5279): 	at kfv.a(PG:65)
E/HttpOperation( 5279): 	at kff.u(PG:385)
E/HttpOperation( 5279): 	at kfb.a(PG:29)
E/HttpOperation( 5279): 	at ixd.a(PG:248)
E/HttpOperation( 5279): 	at ixd.b(PG:206)
E/HttpOperation( 5279): 	at ixd.a(PG:175)
E/HttpOperation( 5279): 	at fig.a(PG:78)
E/HttpOperation( 5279): 	at lex.a(PG:85)
E/HttpOperation( 5279): 	at lex.b(PG:132)
E/HttpOperation( 5279): 	at fhk.a(PG:1146)
E/HttpOperation( 5279): 	at fhk.a(PG:908)
E/HttpOperation( 5279): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5279): 	at ihi.a(PG:22)
E/HttpOperation( 5279): 	at kft.a(PG:91)
E/HttpOperation( 5279): 	at kfv.a(PG:62)
E/HttpOperation( 5279): 	... 12 more
E/HttpOperation( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5279): 	at gde.c(Unknown Source)
E/HttpOperation( 5279): 	at gde.b(Unknown Source)
E/HttpOperation( 5279): 	at ihi.a(PG:19)
E/HttpOperation( 5279): 	... 14 more
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/EsSyncAdapterService( 5279): Sync failure
E/EsSyncAdapterService( 5279): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5279): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5279): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5279): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5279): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5279): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5279): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5279): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5279): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5279): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5279): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5279): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5279): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5279): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5279): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5279): 	... 10 more
E/EsSyncAdapterService( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5279): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5279): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5279): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5279): 	... 12 more
E/EsSyncAdapterService( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5279): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5279): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5279): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5279): 	... 14 more
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  888): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 281750, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  888): Explicit concurrent mark sweep GC freed 48348(2MB) AllocSpace objects, 49(1239KB) LOS objects, 29% free, 37MB/53MB, paused 1.973ms total 193.682ms
,D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  888): mCursor = null
,E/SQLiteLog( 1672): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 9
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  888): [PWL] Off : 180s ago
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 296, CUR = 300
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  289): DCD ON
,D/TimaService(  888): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  888): TimaServiceHandler.handleMessage what =1
,D/TimaService(  888): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  888): initializing...
,I/TLC_TIMA_PKM_initialize(  888): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  888): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  888): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  888): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  888): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  888): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  888): max_message_size = 524416 = 0x80080,
,D/QSEECOMAPI: (  888): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  888): App is not loaded in QSEE,
,D/QSEECOMAPI: (  888): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  888): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  888): Trustlet response is completed
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  888): waitForAlarm result :4
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  888): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  888): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  888): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  888): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 293, CUR = 300
,E/SMD     (  289): DCD ON
,I/Atfwd_Sendcmd(  343): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  343): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager(  888): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  888): waitForAlarm result :4
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0,
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  888): stay LED for fully charged
,I/ActivityManager(  888): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8073 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,E/Zygote  ( 8073): MountEmulatedStorage()
,E/Zygote  ( 8073): v2
I/libpersona( 8073): KNOX_SDCARD checking this for 10081
I/libpersona( 8073): KNOX_SDCARD not a persona
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,I/SELinux ( 8073): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8073): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,E/SELinux ( 8073): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 8073): TimaSignature is unavailable
,D/ActivityThread( 8073): Added TimaKeyStore provider
,D/ResourcesManager( 8073): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  888): Killing 6873:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,W/libprocessgroup(  888): failed to open /acct/uid_10099/pid_6873/cgroup.procs: No such file or directory
,I/PowerManagerService(  888): [PWL] Off : 225s ago
,E/SMD     (  289): DCD ON
,I/ActivityManager(  888): Killing 6941:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,W/libprocessgroup(  888): failed to open /acct/uid_10020/pid_6941/cgroup.procs: No such file or directory
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,V/AlarmManager(  888): waitForAlarm result :4
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7581): Starting books sync, d
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1672): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1672): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1672): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1672): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7581): Authentication error
E/BooksAccountManager( 7581): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7581): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7581): null auth token
,I/qtaguid ( 7581): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
,I/qtaguid ( 7581): Untagging socket 34
,W/ApiaryClient( 7581): Error response from books API: {
W/ApiaryClient( 7581):  "error": {
W/ApiaryClient( 7581):   "errors": [
W/ApiaryClient( 7581):    {
W/ApiaryClient( 7581):     "domain": "global",
W/ApiaryClient( 7581):     "reason": "required",
W/ApiaryClient( 7581):     "message": "Login Required",
W/ApiaryClient( 7581):     "locationType": "header",
W/ApiaryClient( 7581):     "location": "Authorization"
W/ApiaryClient( 7581):    }
W/ApiaryClient( 7581):   ],
W/ApiaryClient( 7581):   "code": 401,
W/ApiaryClient( 7581):   "message": "Login Required"
W/ApiaryClient( 7581):  }
W/ApiaryClient( 7581): }
,W/ApiaryClient( 7581): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3063223363158769040&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7581): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SQLiteLog( 1672): (10) POSIX Error : 11 SQLite Error : 3850
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  289): DCD ON
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1672): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1672): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1672): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1672): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7581): Authentication error
E/BooksAccountManager( 7581): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7581): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7581): null auth token
,I/qtaguid ( 7581): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
,E/Watchdog(  888): !@Sync 11
,I/qtaguid ( 7581): Untagging socket 34
,W/ApiaryClient( 7581): Error response from books API: {
W/ApiaryClient( 7581):  "error": {
W/ApiaryClient( 7581):   "errors": [
W/ApiaryClient( 7581):    {
W/ApiaryClient( 7581):     "domain": "global",
W/ApiaryClient( 7581):     "reason": "required",
W/ApiaryClient( 7581):     "message": "Login Required",
W/ApiaryClient( 7581):     "locationType": "header",
W/ApiaryClient( 7581):     "location": "Authorization"
W/ApiaryClient( 7581):    }
W/ApiaryClient( 7581):   ],
W/ApiaryClient( 7581):   "code": 401,
W/ApiaryClient( 7581):   "message": "Login Required"
W/ApiaryClient( 7581):  }
W/ApiaryClient( 7581): }
,W/ApiaryClient( 7581): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3063223363158769040&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7581): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1672): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1672): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1672): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1672): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7581): Authentication error
E/BooksAccountManager( 7581): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7581): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7581): null auth token
,I/qtaguid ( 7581): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
,I/qtaguid ( 7581): Untagging socket 34
,W/ApiaryClient( 7581): Error response from books API: {
W/ApiaryClient( 7581):  "error": {
W/ApiaryClient( 7581):   "errors": [
W/ApiaryClient( 7581):    {
W/ApiaryClient( 7581):     "domain": "global",
W/ApiaryClient( 7581):     "reason": "required",
W/ApiaryClient( 7581):     "message": "Login Required",
W/ApiaryClient( 7581):     "locationType": "header",
W/ApiaryClient( 7581):     "location": "Authorization"
W/ApiaryClient( 7581):    }
W/ApiaryClient( 7581):   ],
W/ApiaryClient( 7581):   "code": 401,
W/ApiaryClient( 7581):   "message": "Login Required"
W/ApiaryClient( 7581):  }
W/ApiaryClient( 7581): }
,W/ApiaryClient( 7581): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3063223363158769040&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7581): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7581): Soft error
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3063223363158769040&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7581): Headers suppressed
E/BooksSync( 7581): 
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7581): Sync error
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3063223363158769040&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7581): Headers suppressed
E/BooksSync( 7581): 
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7581): Finished books sync
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  888): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 318560, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  888): mCursor = null
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1672): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1672): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1672): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1672): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1672): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6569): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6569): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6569): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6569): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6569): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6569): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6569): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 6569): Ignoring header User-Agent because its value was null.
,I/System.out( 6569): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6569): (HTTPLog)-Static: isShipBuild true
I/System.out( 6569): (HTTPLog)-Thread-1068-542926619: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  888): waitForAlarm result :4
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 12
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON,
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/PowerManagerService(  888): [PWL] Off : 275s ago
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,V/AlarmManager(  888): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 13
,E/SMD     (  289): DCD ON
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 14
,E/SMD     (  289): DCD ON
,I/Atfwd_Sendcmd(  343): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  343): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  888): [PWL] Off : 330s ago
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 15
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/bootchecker(  330): bootchecker wake up!!
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 16
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  888): [PWL] Off : 390s ago
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  289): DCD ON
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  888): !@Sync 17
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,I/ServiceManager(  343): Waiting for service AtCmdFwd...
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  343): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1672): Explicit concurrent mark sweep GC freed 43079(2MB) AllocSpace objects, 59(4MB) LOS objects, 40% free, 18MB/30MB, paused 896us total 104.483ms
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1672): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 5279): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5279): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5279): 	at kfv.a(PG:65)
E/HttpOperation( 5279): 	at kff.u(PG:385)
E/HttpOperation( 5279): 	at kfb.a(PG:29)
E/HttpOperation( 5279): 	at kff.l(PG:132)
E/HttpOperation( 5279): 	at dsf.a(PG:807)
E/HttpOperation( 5279): 	at fhk.a(PG:1126)
E/HttpOperation( 5279): 	at fhk.a(PG:908)
E/HttpOperation( 5279): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5279): 	at ihi.a(PG:22)
E/HttpOperation( 5279): 	at kft.a(PG:91)
E/HttpOperation( 5279): 	at kfv.a(PG:62)
E/HttpOperation( 5279): 	... 8 more
E/HttpOperation( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5279): 	at gde.c(Unknown Source)
E/HttpOperation( 5279): 	at gde.b(Unknown Source)
E/HttpOperation( 5279): 	at ihi.a(PG:19)
E/HttpOperation( 5279): 	... 10 more
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
,D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 5279): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5279): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5279): 	at kfv.a(PG:65)
E/HttpOperation( 5279): 	at kff.u(PG:385)
E/HttpOperation( 5279): 	at kfb.a(PG:29)
E/HttpOperation( 5279): 	at kff.l(PG:132)
E/HttpOperation( 5279): 	at ieo.a(PG:43)
E/HttpOperation( 5279): 	at iep.a(PG:93)
E/HttpOperation( 5279): 	at fhn.a(PG:59)
E/HttpOperation( 5279): 	at lex.a(PG:85)
E/HttpOperation( 5279): 	at lex.b(PG:132)
E/HttpOperation( 5279): 	at fhk.a(PG:1146)
E/HttpOperation( 5279): 	at fhk.a(PG:908)
E/HttpOperation( 5279): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5279): 	at ihi.a(PG:22)
E/HttpOperation( 5279): 	at kft.a(PG:91)
E/HttpOperation( 5279): 	at kfv.a(PG:62)
E/HttpOperation( 5279): 	... 12 more
E/HttpOperation( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5279): 	at gde.c(Unknown Source)
E/HttpOperation( 5279): 	at gde.b(Unknown Source)
E/HttpOperation( 5279): 	at ihi.a(PG:19)
E/HttpOperation( 5279): 	... 14 more
,E/ExperimentLoader( 5279): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5279): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5279): 	at kfv.a(PG:65)
E/ExperimentLoader( 5279): 	at kff.u(PG:385)
E/ExperimentLoader( 5279): 	at kfb.a(PG:29)
E/ExperimentLoader( 5279): 	at kff.l(PG:132)
E/ExperimentLoader( 5279): 	at ieo.a(PG:43)
E/ExperimentLoader( 5279): 	at iep.a(PG:93)
E/ExperimentLoader( 5279): 	at fhn.a(PG:59)
E/ExperimentLoader( 5279): 	at lex.a(PG:85)
E/ExperimentLoader( 5279): 	at lex.b(PG:132)
E/ExperimentLoader( 5279): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5279): 	at fhk.a(PG:908)
E/ExperimentLoader( 5279): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5279): 	at ihi.a(PG:22)
E/ExperimentLoader( 5279): 	at kft.a(PG:91)
E/ExperimentLoader( 5279): 	at kfv.a(PG:62)
E/ExperimentLoader( 5279): 	... 12 more
E/ExperimentLoader( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5279): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5279): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5279): 	at ihi.a(PG:19)
E/ExperimentLoader( 5279): 	... 14 more
E/SQLiteLog( 1672): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 5279): [getaccountstatus] Unexpected exception
E/HttpOperation( 5279): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5279): 	at kfv.a(PG:65)
E/HttpOperation( 5279): 	at kff.u(PG:385)
E/HttpOperation( 5279): 	at kfb.a(PG:29)
E/HttpOperation( 5279): 	at ixd.a(PG:248)
E/HttpOperation( 5279): 	at ixd.b(PG:206)
E/HttpOperation( 5279): 	at ixd.a(PG:175)
E/HttpOperation( 5279): 	at fig.a(PG:78)
E/HttpOperation( 5279): 	at lex.a(PG:85)
E/HttpOperation( 5279): 	at lex.b(PG:132)
E/HttpOperation( 5279): 	at fhk.a(PG:1146)
E/HttpOperation( 5279): 	at fhk.a(PG:908)
E/HttpOperation( 5279): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5279): 	at ihi.a(PG:22)
E/HttpOperation( 5279): 	at kft.a(PG:91)
E/HttpOperation( 5279): 	at kfv.a(PG:62)
E/HttpOperation( 5279): 	... 12 more
E/HttpOperation( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5279): 	at gde.c(Unknown Source)
E/HttpOperation( 5279): 	at gde.b(Unknown Source)
E/HttpOperation( 5279): 	at ihi.a(PG:19)
E/HttpOperation( 5279): 	... 14 more
,E/EsSyncAdapterService( 5279): Sync failure
E/EsSyncAdapterService( 5279): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5279): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5279): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5279): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5279): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5279): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5279): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5279): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5279): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5279): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5279): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5279): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5279): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5279): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5279): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5279): 	... 10 more
E/EsSyncAdapterService( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5279): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5279): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5279): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5279): 	... 12 more
E/EsSyncAdapterService( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5279): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5279): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5279): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5279): 	... 14 more
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  888): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 533664, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  888): mCursor = null
,E/SQLiteLog( 1672): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 18
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/Atfwd_Sendcmd(  343): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  343): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  888): stay LED for fully charged
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,I/PowerManagerService(  888): [PWL] Off : 455s ago
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager(  888): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,I/Atfwd_Daemon(  343): Stop the daemon....
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 19
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7581): Starting books sync, d
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1672): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
,D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1672): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1672): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1672): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1672): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/BooksAccountManager( 7581): Authentication error
E/BooksAccountManager( 7581): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7581): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7581): null auth token
,I/qtaguid ( 7581): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
,E/SMD     (  289): DCD ON
,I/qtaguid ( 7581): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
,I/qtaguid ( 7581): Untagging socket 34
,W/ApiaryClient( 7581): Error response from books API: {
W/ApiaryClient( 7581):  "error": {
W/ApiaryClient( 7581):   "errors": [
W/ApiaryClient( 7581):    {
W/ApiaryClient( 7581):     "domain": "global",
W/ApiaryClient( 7581):     "reason": "required",
W/ApiaryClient( 7581):     "message": "Login Required",
W/ApiaryClient( 7581):     "locationType": "header",
W/ApiaryClient( 7581):     "location": "Authorization"
W/ApiaryClient( 7581):    }
W/ApiaryClient( 7581):   ],
W/ApiaryClient( 7581):   "code": 401,
W/ApiaryClient( 7581):   "message": "Login Required"
W/ApiaryClient( 7581):  }
W/ApiaryClient( 7581): }
,W/ApiaryClient( 7581): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3593996298684398715&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7581): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1672): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1672): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1672): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1672): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7581): Authentication error
E/BooksAccountManager( 7581): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7581): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7581): null auth token
,I/qtaguid ( 7581): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
,I/qtaguid ( 7581): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
,I/qtaguid ( 7581): Untagging socket 34
,W/ApiaryClient( 7581): Error response from books API: {
W/ApiaryClient( 7581):  "error": {
W/ApiaryClient( 7581):   "errors": [
W/ApiaryClient( 7581):    {
W/ApiaryClient( 7581):     "domain": "global",
W/ApiaryClient( 7581):     "reason": "required",
W/ApiaryClient( 7581):     "message": "Login Required",
W/ApiaryClient( 7581):     "locationType": "header",
W/ApiaryClient( 7581):     "location": "Authorization"
W/ApiaryClient( 7581):    }
W/ApiaryClient( 7581):   ],
W/ApiaryClient( 7581):   "code": 401,
W/ApiaryClient( 7581):   "message": "Login Required"
W/ApiaryClient( 7581):  }
W/ApiaryClient( 7581): }
W/ApiaryClient( 7581): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3593996298684398715&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7581): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1672): (10) POSIX Error : 11 SQLite Error : 3850
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1672): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1672): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1672): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1672): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7581): Authentication error
E/BooksAccountManager( 7581): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7581): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7581): null auth token
,I/qtaguid ( 7581): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
,I/qtaguid ( 7581): Untagging socket 34
,W/ApiaryClient( 7581): Error response from books API: {
W/ApiaryClient( 7581):  "error": {
W/ApiaryClient( 7581):   "errors": [
W/ApiaryClient( 7581):    {
W/ApiaryClient( 7581):     "domain": "global",
W/ApiaryClient( 7581):     "reason": "required",
W/ApiaryClient( 7581):     "message": "Login Required",
W/ApiaryClient( 7581):     "locationType": "header",
W/ApiaryClient( 7581):     "location": "Authorization"
W/ApiaryClient( 7581):    }
W/ApiaryClient( 7581):   ],
W/ApiaryClient( 7581):   "code": 401,
W/ApiaryClient( 7581):   "message": "Login Required"
W/ApiaryClient( 7581):  }
W/ApiaryClient( 7581): }
,W/ApiaryClient( 7581): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3593996298684398715&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7581): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,E/BooksSync( 7581): Soft error
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3593996298684398715&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7581): Headers suppressed
E/BooksSync( 7581): 
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7581): Sync error
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3593996298684398715&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7581): Headers suppressed
E/BooksSync( 7581): 
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7581): Finished books sync
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  888): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 604185, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  888): Explicit concurrent mark sweep GC freed 61400(4MB) AllocSpace objects, 108(2MB) LOS objects, 29% free, 37MB/53MB, paused 1.771ms total 147.783ms
D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  888): mCursor = null
,E/SMD     (  289): DCD ON
,D/TimaService(  888): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  888): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  888): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  888): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  888): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  888): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  888): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :8
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,W/ContextImpl(  888): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  888): [PWL] Off : 525s ago
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 21
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON,
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 22
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 23
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  888): [PWL] Off : 600s ago
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 24
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 25
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  888): [PWL] Off : 680s ago
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 26
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/Finsky  ( 6569): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/LightsService(  888): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  888): stay LED for fully charged
,E/LightSensor(  888): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  888): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6569): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  888): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  888): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  888): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  888): unregisterListener ::   
D/LightsService(  888): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6569): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6569): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6569): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6569): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6569): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/DeviceConnectionService( 2178): client connected with version: 7571000
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  888): stay LED for fully charged
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6569): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6569): [1] 5.onFinished: Scheduling replication attempt 1.
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 27
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6569): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6569): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true,
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 28
,V/AlarmManager(  888): waitForAlarm result :4
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  888): stay LED for fully charged
D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6569): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6569): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,I/PowerManagerService(  888): [PWL] Off : 765s ago
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  888): stay LED for fully charged
D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD ON
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6569): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6569): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 29
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,E/SMD     (  289): DCD ON
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6569): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6569): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/TimaService(  888): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  888): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  888): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  888): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  888): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  888): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  888): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  888): stay LED for fully charged
D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1672): Explicit concurrent mark sweep GC freed 38817(2MB) AllocSpace objects, 14(1134KB) LOS objects, 39% free, 18MB/30MB, paused 555us total 36.458ms
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6569): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6569): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 31
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,I/PowerManagerService(  888): [PWL] Off : 855s ago
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 32
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 33
,E/SMD     (  289): DCD ON
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 34
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  888): stay LED for fully charged
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD ON
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1672): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
,D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 5279): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5279): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5279): 	at kfv.a(PG:65)
E/HttpOperation( 5279): 	at kff.u(PG:385)
E/HttpOperation( 5279): 	at kfb.a(PG:29)
E/HttpOperation( 5279): 	at kff.l(PG:132)
E/HttpOperation( 5279): 	at dsf.a(PG:807)
E/HttpOperation( 5279): 	at fhk.a(PG:1126)
E/HttpOperation( 5279): 	at fhk.a(PG:908)
E/HttpOperation( 5279): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5279): 	at ihi.a(PG:22)
E/HttpOperation( 5279): 	at kft.a(PG:91)
E/HttpOperation( 5279): 	at kfv.a(PG:62)
E/HttpOperation( 5279): 	... 8 more
E/HttpOperation( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5279): 	at gde.c(Unknown Source)
E/HttpOperation( 5279): 	at gde.b(Unknown Source)
E/HttpOperation( 5279): 	at ihi.a(PG:19)
E/HttpOperation( 5279): 	... 10 more
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
,D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5279): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5279): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5279): 	at kfv.a(PG:65)
E/HttpOperation( 5279): 	at kff.u(PG:385)
E/HttpOperation( 5279): 	at kfb.a(PG:29)
E/HttpOperation( 5279): 	at kff.l(PG:132)
E/HttpOperation( 5279): 	at ieo.a(PG:43)
E/HttpOperation( 5279): 	at iep.a(PG:93)
E/HttpOperation( 5279): 	at fhn.a(PG:59)
E/HttpOperation( 5279): 	at lex.a(PG:85)
E/HttpOperation( 5279): 	at lex.b(PG:132)
E/HttpOperation( 5279): 	at fhk.a(PG:1146)
E/HttpOperation( 5279): 	at fhk.a(PG:908)
E/HttpOperation( 5279): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5279): 	at ihi.a(PG:22)
E/HttpOperation( 5279): 	at kft.a(PG:91)
E/HttpOperation( 5279): 	at kfv.a(PG:62)
E/HttpOperation( 5279): 	... 12 more
E/HttpOperation( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5279): 	at gde.c(Unknown Source)
E/HttpOperation( 5279): 	at gde.b(Unknown Source)
E/HttpOperation( 5279): 	at ihi.a(PG:19)
E/HttpOperation( 5279): 	... 14 more
,E/ExperimentLoader( 5279): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5279): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5279): 	at kfv.a(PG:65)
E/ExperimentLoader( 5279): 	at kff.u(PG:385)
E/ExperimentLoader( 5279): 	at kfb.a(PG:29)
E/ExperimentLoader( 5279): 	at kff.l(PG:132)
E/ExperimentLoader( 5279): 	at ieo.a(PG:43)
E/ExperimentLoader( 5279): 	at iep.a(PG:93)
E/ExperimentLoader( 5279): 	at fhn.a(PG:59)
E/ExperimentLoader( 5279): 	at lex.a(PG:85)
E/ExperimentLoader( 5279): 	at lex.b(PG:132)
E/ExperimentLoader( 5279): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5279): 	at fhk.a(PG:908)
E/ExperimentLoader( 5279): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5279): 	at ihi.a(PG:22)
E/ExperimentLoader( 5279): 	at kft.a(PG:91)
E/ExperimentLoader( 5279): 	at kfv.a(PG:62)
E/ExperimentLoader( 5279): 	... 12 more
E/ExperimentLoader( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5279): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5279): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5279): 	at ihi.a(PG:19)
E/ExperimentLoader( 5279): 	... 14 more
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
D/SecContentProvider2(  888): mCursor = null
,D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 5279): [getaccountstatus] Unexpected exception
E/HttpOperation( 5279): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5279): 	at kfv.a(PG:65)
E/HttpOperation( 5279): 	at kff.u(PG:385)
E/HttpOperation( 5279): 	at kfb.a(PG:29)
E/HttpOperation( 5279): 	at ixd.a(PG:248)
E/HttpOperation( 5279): 	at ixd.b(PG:206)
E/HttpOperation( 5279): 	at ixd.a(PG:175)
E/HttpOperation( 5279): 	at fig.a(PG:78)
E/HttpOperation( 5279): 	at lex.a(PG:85)
E/HttpOperation( 5279): 	at lex.b(PG:132)
E/HttpOperation( 5279): 	at fhk.a(PG:1146)
E/HttpOperation( 5279): 	at fhk.a(PG:908)
E/HttpOperation( 5279): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5279): 	at ihi.a(PG:22)
E/HttpOperation( 5279): 	at kft.a(PG:91)
E/HttpOperation( 5279): 	at kfv.a(PG:62)
E/HttpOperation( 5279): 	... 12 more
E/HttpOperation( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5279): 	at gde.c(Unknown Source)
E/HttpOperation( 5279): 	at gde.b(Unknown Source)
E/HttpOperation( 5279): 	at ihi.a(PG:19)
E/HttpOperation( 5279): 	... 14 more
,E/EsSyncAdapterService( 5279): Sync failure
E/EsSyncAdapterService( 5279): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5279): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5279): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5279): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5279): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5279): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5279): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5279): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5279): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5279): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5279): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5279): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5279): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5279): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5279): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5279): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5279): 	... 10 more
E/EsSyncAdapterService( 5279): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5279): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5279): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5279): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5279): 	... 12 more
E/EsSyncAdapterService( 5279): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5279): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5279): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5279): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5279): 	... 14 more
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  888): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1036461, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  888): Explicit concurrent mark sweep GC freed 63608(4MB) AllocSpace objects, 136(2MB) LOS objects, 29% free, 38MB/54MB, paused 1.597ms total 116.914ms
,D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  888): mCursor = null
,E/SQLiteLog( 1672): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  888): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  888): [PWL] Off : 950s ago
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 35
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  888): stay LED for fully charged
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 36
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  888): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 37
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7581): Starting books sync, d
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1672): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
,D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1672): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1672): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1672): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1672): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7581): Authentication error
E/BooksAccountManager( 7581): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7581): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7581): null auth token
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/qtaguid ( 7581): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
,I/qtaguid ( 7581): Untagging socket 34
,W/ApiaryClient( 7581): Error response from books API: {
W/ApiaryClient( 7581):  "error": {
W/ApiaryClient( 7581):   "errors": [
W/ApiaryClient( 7581):    {
W/ApiaryClient( 7581):     "domain": "global",
W/ApiaryClient( 7581):     "reason": "required",
W/ApiaryClient( 7581):     "message": "Login Required",
W/ApiaryClient( 7581):     "locationType": "header",
W/ApiaryClient( 7581):     "location": "Authorization"
W/ApiaryClient( 7581):    }
W/ApiaryClient( 7581):   ],
W/ApiaryClient( 7581):   "code": 401,
W/ApiaryClient( 7581):   "message": "Login Required"
W/ApiaryClient( 7581):  }
W/ApiaryClient( 7581): }
,W/ApiaryClient( 7581): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5475306792658999843&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7581): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1672): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1672): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1672): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1672): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/BooksAccountManager( 7581): Authentication error
E/BooksAccountManager( 7581): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7581): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7581): null auth token
,I/qtaguid ( 7581): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
,I/qtaguid ( 7581): Tagging socket 40 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
,I/qtaguid ( 7581): Untagging socket 34
,W/ApiaryClient( 7581): Error response from books API: {
W/ApiaryClient( 7581):  "error": {
W/ApiaryClient( 7581):   "errors": [
W/ApiaryClient( 7581):    {
W/ApiaryClient( 7581):     "domain": "global",
W/ApiaryClient( 7581):     "reason": "required",
W/ApiaryClient( 7581):     "message": "Login Required",
W/ApiaryClient( 7581):     "locationType": "header",
W/ApiaryClient( 7581):     "location": "Authorization"
W/ApiaryClient( 7581):    }
W/ApiaryClient( 7581):   ],
W/ApiaryClient( 7581):   "code": 401,
W/ApiaryClient( 7581):   "message": "Login Required"
W/ApiaryClient( 7581):  }
W/ApiaryClient( 7581): }
,W/ApiaryClient( 7581): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5475306792658999843&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7581): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1672): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1672): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1672): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1672): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1672): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1672): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  888): uri = 14 selection = getSealedState
,D/SecContentProvider2(  888): mCursor = null
D/SecContentProvider2(  888): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  888): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  888): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1672): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1672): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1672): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1672): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1672): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7581): Authentication error
E/BooksAccountManager( 7581): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7581): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7581): null auth token
,I/qtaguid ( 7581): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7581, getuid(): 10082
,I/qtaguid ( 7581): Untagging socket 34
,W/ApiaryClient( 7581): Error response from books API: {
W/ApiaryClient( 7581):  "error": {
W/ApiaryClient( 7581):   "errors": [
W/ApiaryClient( 7581):    {
W/ApiaryClient( 7581):     "domain": "global",
W/ApiaryClient( 7581):     "reason": "required",
W/ApiaryClient( 7581):     "message": "Login Required",
W/ApiaryClient( 7581):     "locationType": "header",
W/ApiaryClient( 7581):     "location": "Authorization"
W/ApiaryClient( 7581):    }
W/ApiaryClient( 7581):   ],
W/ApiaryClient( 7581):   "code": 401,
W/ApiaryClient( 7581):   "message": "Login Required"
W/ApiaryClient( 7581):  }
W/ApiaryClient( 7581): }
,W/ApiaryClient( 7581): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5475306792658999843&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7581): Headers suppressed
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7581): Soft error
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5475306792658999843&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7581): Headers suppressed
E/BooksSync( 7581): 
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7581): Sync error
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7581): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5475306792658999843&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7581): Headers suppressed
E/BooksSync( 7581): 
E/BooksSync( 7581): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7581): Finished books sync
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  888): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1124701, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  888): mCursor = null
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON,
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 38
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  888): waitForAlarm result :4
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  888): [PWL] Off : 1050s ago
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  888): waitForAlarm result :8
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 39
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 280, PST = 288, CUR = 300
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 280, PST = 287, CUR = 300
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 280, PST = 286, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/TimaService(  888): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  888): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  888): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  888): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  888): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  888): Updating Usage Statistics in DB @ 1449589606749
,I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
,W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
,W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
,W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
,W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
,W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
,W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
,W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
,W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
,W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  888): ::getAppControlDB: Exception to create DB
W/System.err(  888): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  888): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  888): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  888): Done Updating Usage Statistics in DB @ 1449589607047
,I/TLC_TIMA_PKM_measure_kernel(  888): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  888): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  888): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  888): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  888): !@Sync 40
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 286, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 286, CUR = 300
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 286, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 41
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 280, PST = 285, CUR = 300
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 280, PST = 284, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged,
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  888): [PWL] Off : 1155s ago
,D/SSRM:m  (  888): SIOP:: AP = 280, PST = 283, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 42
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 282, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 281, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 280, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true,
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 43
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 279, CUR = 300
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 277, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 44
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 273, CUR = 300
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 271, CUR = 300
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 45
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  888): [PWL] Off : 1265s ago
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 46
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/LightsService(  888): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  888): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  888): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1672): Message class com.google.f.a.a.i
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/PerfProfileCollectorService( 2464): User is not opt-in to Usage & Diagnostics.
,D/PerfProfileCollectorService( 2464): removeStateFiles() called
,I/GoogleURLConnFactory( 1672): Using platform SSLCertificateSocketFactory
,D/PerfProfileCollectorService( 2464): User is not opt-in to Usage & Diagnostics.
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  888): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  888): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  888): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  888): unregisterListener ::   
D/LightsService(  888): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :8
,D/SSRM:m  (  888): SIOP:: AP = 280, PST = 271, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true,
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 47
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 48
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 49
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  888): [PWL] Off : 1380s ago
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService(  888): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  888): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService(  888): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  888): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel(  888): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  888): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  888): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  888): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 272, CUR = 300
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,E/SMD     (  289): DCD ON
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD ON
,V/AlarmManager(  888): waitForAlarm result :8
,D/SSRM:m  (  888): SIOP:: AP = 280, PST = 273, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 51
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 52
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  888): !@Sync 53
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  289): DCD ON
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  888): [PWL] Off : 1500s ago
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  888): !@Sync 54
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  888): !@Sync 55
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 56
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  888): !@Sync 57
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  888): [PWL] Off : 1625s ago
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  888): !@Sync 58
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 59
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  888): stay LED for fully charged
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,D/NetworkStatsFactory(  888): UpdateStatsForKnox
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/TimaService(  888): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  888): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  888): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  888): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel(  888): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  888): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  888): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  888): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 290, PST = 272, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,E/Watchdog(  888): !@Sync 61
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/ConnectivityService(  888): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  888): [PWL] Off : 1755s ago
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 62
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  888): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  888): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  888): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  888): stay LED for fully charged
,D/BatteryService(  888): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/MotionRecognitionService(  888):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  888): Plugged
,I/MotionRecognitionService(  888): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3232): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3232): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:m  (  888): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  888): !@Sync 63
,E/SMD     (  289): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8526): 
D/AndroidRuntime( 8526): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8526): CheckJNI is OFF
D/AndroidRuntime( 8526): setted country_code = Germany
D/AndroidRuntime( 8526): setted countryiso_code = DE
D/AndroidRuntime( 8526): setted sales_code = DBT
D/AndroidRuntime( 8526): readGMSProperty: start
D/AndroidRuntime( 8526): readGMSProperty: already setted!!
D/AndroidRuntime( 8526): readGMSProperty: end
D/AndroidRuntime( 8526): addProductProperty: start
E/AffinityControl( 8526): AffinityControl: registerfunction enter
D/AndroidRuntime( 8526): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  888): START PACKAGE DELETE: observer{393667396}
D/PackageManager(  888): pkg{<packageName>}
D/PackageManager(  888): user{0}
D/PackageManager(  888): caller{2000}
D/PackageManager(  888): flags{3}
D/PersonaManagerService(  888): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  888): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  888): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  888): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  888): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  888): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  888): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  888): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  888): getApplicationUninstallationEnabled
D/ApplicationPolicy(  888): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  888): !@killApplicatoin: 10367, uninstall pkg
I/ActivityManager(  888): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
I/ActivityManager(  888): Killing 7649:com.test.thalitest/u0a367 (adj 15): stop com.test.thalitest
I/ActivityManager(  888): Killing 7261:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): empty for 1808s
I/ActivityManager(  888): Killing 6742:com.android.mms/u0a50 (adj 15): empty for 1808s
I/ActivityManager(  888): Killing 5871:com.sec.android.gallery3d/u0a48 (adj 15): empty for 1808s
I/ActivityManager(  888): Killing 7482:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1809s
I/ActivityManager(  888): Killing 7455:com.android.calendar/u0a150 (adj 15): empty for 1823s
I/ActivityManager(  888): Killing 7440:com.sec.android.widgetapp.SPlannerAppWidget/u0a149 (adj 15): empty for 1823s
I/ActivityManager(  888): Killing 7476:com.android.providers.calendar/u0a46 (adj 15): empty for 1824s
I/ActivityManager(  888): Killing 7534:com.qualcomm.timeservice/1000 (adj 15): empty for 1824s
I/ActivityManager(  888): Killing 7517:com.sec.android.app.taskmanager/u0a176 (adj 15): empty for 1824s
I/ActivityManager(  888): Killing 7423:com.sec.esdk.elm/u0a104 (adj 15): empty for 1825s
I/ActivityManager(  888): Killing 7408:com.sec.android.app.clockpackage/u0a91 (adj 15): empty for 1825s
I/ActivityManager(  888): Killing 7386:com.samsung.android.scloud.sync/u0a67 (adj 15): empty for 1825s
I/ActivityManager(  888): Killing 6718:com.osp.app.signin/u0a45 (adj 15): empty for 1825s
I/ActivityManager(  888): Killing 7370:com.sec.android.soagent/u0a37 (adj 15): empty for 1826s
I/ActivityManager(  888): Killing 4729:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1826s
I/ActivityManager(  888): Killing 7355:com.samsung.klmsagent/u0a19 (adj 15): empty for 1826s
I/ActivityManager(  888): Killing 7339:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1826s
I/ActivityManager(  888): Killing 5098:com.android.defcontainer/u0a5 (adj 15): empty for 1837s
I/ActivityManager(  888): Killing 4815:com.google.android.gms.wearable/u0a12 (adj 15): empty for 1839s
I/ActivityManager(  888): Killing 7109:com.sec.android.app.samsungapps/u0a40 (adj 15): empty for 1844s
I/ActivityManager(  888): Killing 7086:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): empty for 1844s
I/ActivityManager(  888): Killing 6609:com.google.android.gms:car/u0a12 (adj 15): empty for 1844s
I/ActivityManager(  888): Killing 7070:com.sec.kidsplat.installer/u0a166 (adj 15): empty for 1844s
I/ActivityManager(  888): Killing 7034:com.samsung.helphub/1000 (adj 15): empty for 1845s
I/ActivityManager(  888): Killing 7018:com.samsung.android.magazine.service/u0a118 (adj 15): empty for 1845s
I/ActivityManager(  888): Killing 6998:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): empty for 1845s
I/ActivityManager(  888): Killing 6975:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1845s
I/ActivityManager(  888): Killing 6952:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty for 1845s
I/ProcessStatsService(  888): Prepared write state in 8ms
D/CountryDetector(  888): No listener is left
W/PackageSettings(  888): Skipping PackageSetting{e2e15b3 com.example.hello/10374} due to missing metadata
I/ActivityManager(  888): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
I/art     ( 4582): Explicit concurrent mark sweep GC freed 3635(203KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 14MB/24MB, paused 305us total 16.104ms
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/art     ( 1557): Explicit concurrent mark sweep GC freed 11038(738KB) AllocSpace objects, 3(728KB) LOS objects, 39% free, 16MB/27MB, paused 1.572ms total 31.672ms
I/InputReader(  888): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1847): mOCRHelper is null
W/GeofencerStateMachine( 2178): Ignoring removeGeofence because network location is disabled.
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8556): MountEmulatedStorage()
E/Zygote  ( 8556): v2
I/libpersona( 8556): KNOX_SDCARD checking this for 10019
I/libpersona( 8556): KNOX_SDCARD not a persona
I/ActivityManager(  888): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8556 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/ProcessStatsService(  888): Pruning old procstats: /data/system/procstats/state-2015-12-07-19-33-43.bin
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/SELinux ( 8556): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8556): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8556): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 2865): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/TimaKeyStoreProvider( 8556): TimaSignature is unavailable
D/ActivityThread( 8556): Added TimaKeyStore provider
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager( 8556): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/KLMS-2.4.503: ( 8556): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.503: ( 8556): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449590301782
I/art     (  888): Explicit concurrent mark sweep GC freed 88113(8MB) AllocSpace objects, 276(4MB) LOS objects, 29% free, 38MB/54MB, paused 2.889ms total 184.855ms
D/ResourcesManager(  888): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  888): WaitForGcToComplete blocked for 173.185ms for cause Explicit
I/KLMS-2.4.503: ( 8556): MainReciver(): PACKAGE_REMOVED
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/KLMS-2.4.503: ( 8556): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager( 2865): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
E/SMD     (  289): DCD ON
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/SecContentProvider2(  888): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  888): mCursor = null
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/RegisteredServicesCache( 1456): empty dynamic service
D/EnterpriseDeviceManagerService(  888): Package has changed for user 0
D/EnterpriseDeviceManagerService(  888): Admin package name: com.google.android.gms
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/Zygote  ( 8572): MountEmulatedStorage()
E/Zygote  ( 8572): v2
I/libpersona( 8572): KNOX_SDCARD checking this for 10104
I/libpersona( 8572): KNOX_SDCARD not a persona
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/ActivityManager(  888): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8572 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  888): Killing 7287:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): empty for 1809s
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/SELinux ( 8572): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8572): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux ( 8572): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/TimaKeyStoreProvider( 8572): TimaSignature is unavailable
D/ActivityThread( 8572): Added TimaKeyStore provider
D/ResourcesManager( 8572): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
I/art     (  888): Explicit concurrent mark sweep GC freed 13848(662KB) AllocSpace objects, 0(0B) LOS objects, 29% free, 37MB/53MB, paused 1.854ms total 189.415ms
D/elm:14451( 8572): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8572): ELMEngine.ELMEngine( context ).
D/elm:14451( 8572): MDMBridge.setEnterpriseBridge()
D/elm:14451( 8572): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8587): MountEmulatedStorage()
E/Zygote  ( 8587): v2
I/libpersona( 8587): KNOX_SDCARD checking this for 10017
I/libpersona( 8587): KNOX_SDCARD not a persona
D/elm:14451( 8572): ElmAgentService : onCreate()
D/elm:14451( 8572): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8572): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8572): MDMBridge.getInstance()
I/ActivityManager(  888): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8587 uid=10017 gids={50017, 9997} abi=armeabi-v7a
D/elm:14451( 8572): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  888): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/SELinux ( 8587): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8587): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/elm:14451( 8572): MDMBridge.getAllLicenseInfoFromSDK()
E/SELinux ( 8587): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8587): TimaSignature is unavailable
D/ActivityThread( 8587): Added TimaKeyStore provider
D/elm:14451( 8572): ElmAgentService : onDestroy().
D/RCPManagerService(  888): PackageReceiver onReceive()
I/HarmonyEASService(  888): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/ActivityManager(  888): Killing 7255:com.sec.android.widgetapp.ap.hero.accuweather/u0a71 (adj 15): empty for 1809s
D/KnoxMUMContainerPolicy(  888): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  888): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  888): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  888): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  888): uID is 10367
V/EnterpriseBillingPolicy(  888): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  888): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  888): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  888): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  888): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  888): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  888): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  888): removeObsoleteFile: deleting file=11_task.xml
D/PackageManager(  888): delete codoeFile: 
D/TaskPersister(  888): removeObsoleteFile: deleting file=11_task_thumbnail.png
D/ResourcesManager( 8587): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/PackageManager(  888): result of delete: 1{393667396}
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime( 8526): Shutting down VM
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8587): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8587): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8587): onReceive() : package name is not s health. Return !!!
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Drive/Drive.apk
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
E/Zygote  ( 8605): MountEmulatedStorage()
E/Zygote  ( 8605): v2
I/libpersona( 8605): KNOX_SDCARD checking this for 1000
I/libpersona( 8605): KNOX_SDCARD not a persona
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/ActivityManager(  888): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8605 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  888): Killing 7305:com.sec.android.GeoLookout/u0a113 (adj 15): empty for 1809s
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
I/SELinux ( 8605): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8605): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8605): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(  888): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  888): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  888): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 8605): TimaSignature is unavailable
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityThread( 8605): Added TimaKeyStore provider
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
D/ResourcesManager( 8605): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
I/PCWCLIENTTRACE_LOG( 8605): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 8605): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 8605): new DMDBOpenHelper instance
D/ResourcesManager(  888): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
D/ResourcesManager(  888): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
I/PCWCLIENTTRACE_PushUtil( 8605): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 8605): sales region : global
I/PCWCLIENTTRACE_PushUtil( 8605): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 8605): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  888): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
E/Zygote  ( 8620): MountEmulatedStorage()
E/Zygote  ( 8620): v2
I/libpersona( 8620): KNOX_SDCARD checking this for 10034
I/libpersona( 8620): KNOX_SDCARD not a persona
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
I/ActivityManager(  888): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8620 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  888): Killing 7322:com.sec.android.app.camera/u0a154 (adj 15): empty for 1809s
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  888): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  888): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager(  888): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  888): onPackageRemoved : com.test.thalitest
I/SELinux ( 8620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8620): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8620): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8620): TimaSignature is unavailable
D/ActivityThread( 8620): Added TimaKeyStore provider
D/ResourcesManager( 8620): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
I/FeatureConfig( 8620): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/ResourcesManager( 8620): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager( 8620): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 8620): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager( 8620): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ResourcesManager( 8620): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 8620): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager( 8620): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ResourcesManager( 8620): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 8620): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 8620): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/ResourcesManager( 8620): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/libprocessgroup(  888): failed to open /acct/uid_10067/pid_7386/cgroup.procs: No such file or directory
W/libprocessgroup(  888): failed to open /acct/uid_1000/pid_7034/cgroup.procs: No such file or directory
W/libprocessgroup(  888): failed to open /acct/uid_10035/pid_4729/cgroup.procs: No such file or directory
W/libprocessgroup(  888): failed to open /acct/uid_10166/pid_7070/cgroup.procs: No such file or directory
D/ResourcesManager( 8620): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/libprocessgroup(  888): failed to open /acct/uid_10011/pid_7339/cgroup.procs: No such file or directory

```
